# Status Report da Sprint 2

## 1. Identificação

- **Projeto:** Komanda — sistema de gestão para lancheria com delivery (cliente: Mau Mau Lanches)
- **Número da Sprint:** 2
- **Período:** 24/09 a 08/10
- **Integrantes:** Anna Hermes, Diego Silva, Gabriel Lessa e Lucas Sol
- **Scrum Master da Sprint:** Gabriel Lessa

### Meta da Sprint

Permitir que o atendente cadastre categorias e produtos e consulte o cardápio da Mau Mau Lanches pela aplicação, com o frontend em React consumindo a API em Node.js, e ter o design das telas do MVP validado em um primeiro feedback do cliente.

---

## 2. Resultado da Sprint

### Situação da meta

- [ ] Alcançada
- [x] Parcialmente alcançada
- [ ] Não alcançada

### Resultado alcançado

A API do cardápio está pronta. Ela cadastra, edita, desativa, ordena e exclui categorias, cadastra e edita produtos vinculados a uma categoria e devolve o cardápio montado, com as categorias ativas em ordem e os produtos ativos de cada uma. Todas as rotas seguem o contrato da API, que foi definido antes da implementação.

No frontend, as telas do MVP foram construídas em React: pedido, cardápio com cadastro de produtos, gestão de motoboys e configurações.

A meta ficou parcial porque o frontend ainda guarda os dados no navegador e não consome a API. Também está em um design antigo que ainda precisa ser adaptado pra identidade visual do restaurante do cliente.

### Principal dificuldade ou impedimento

A API de produtos e do cardápio só ficou pronta no fim da sprint. Por isso, o frontend avançou com dados salvos no próprio navegador, e a integração entre as duas partes não aconteceu dentro da sprint.

---

## 3. Itens planejados e situação final

| User Story ou item | Responsável(is) | Situação final | Observação |
|---|---|---|---|
| Contrato da API do MVP | Anna Hermes e Gabriel Lessa | Concluído | PR #10; atualizado para a versão 0.3 no PR #21 |
| Design das telas do MVP | Diego Silva e Lucas Sol | Concluído | Telas na branch `parte-2-projeto` do frontend, ainda não mergeada na `master` |
| Banco de dados das entidades do cardápio | Lucas Sol e Anna Hermes | Concluído | PRs #11 e #12; tabelas criadas por migration |
| US01 – Cadastro de categorias | Anna Hermes e Diego Silva | Em andamento | API concluída no PR #20; a tela ainda não usa a API |
| US02 – Cadastro de produtos | Gabriel Lessa e Lucas Sol | Em andamento | API concluída no PR #21, ainda fora da `main`; a tela ainda não usa a API |
| US03 – Consulta do cardápio | Anna Hermes e Diego Silva | Em andamento | API concluída no PR #22, ainda fora da `main`; a tela ainda não usa a API |
| Primeiro feedback do cliente | Gabriel Lessa | Não iniciado | Issue #19 aberta, sem registro do feedback |

---

## 4. Evidências e qualidade

### Evidências

- **Repositório de backend:** https://github.com/4nnahermes/komanda-backend
- **Repositório de frontend:** https://github.com/LucassolHenrique/Front-end_mau_mau_lanches, com as telas da sprint na branch [parte-2-projeto](https://github.com/LucassolHenrique/Front-end_mau_mau_lanches/tree/parte-2-projeto)
- **Quadro Kanban:** https://github.com/4nnahermes/komanda-backend/issues
- **Deploy ou instruções para executar o projeto:** instruções no README de cada repositório
- **Outras evidências, se necessárias:** [contrato da API](https://github.com/4nnahermes/komanda-backend/blob/feat/fundacao-arquitetura-limpa/docs/api-contrato.md), [arquitetura do backend](https://github.com/4nnahermes/komanda-backend/blob/feat/fundacao-arquitetura-limpa/docs/arquitetura.md) e testes manuais das rotas em `docs/testes/` do backend

### Checklist de qualidade

- [x] Os itens marcados como concluídos atendem aos critérios de aceite.
- [x] As funcionalidades entregues foram testadas pela equipe.
- [x] O código atualizado está no repositório oficial.
- [ ] Os problemas conhecidos estão registrados no Kanban ou no repositório.

### Problemas conhecidos

- **O frontend não está integrado à API.** As telas guardam categorias, produtos e motoboys no navegador.
- **O frontend deve ser adaptado aos contratos de API atualizados**
- **A US01 ainda usa o padrão antigo.** Ela foi feita antes da arquitetura limpa e precisa ser migrada.

---

## 5. Retrospectiva da Sprint

### Manter

Definir o contrato da API antes de implementar, como combinado na retrospectiva anterior. O backend seguiu o contrato sem retrabalho, e os testes automatizados conferem as mensagens e os códigos de resposta de cada rota.

### Melhorar

A integração entre frontend e backend ficou para o fim da sprint. Sem ela, o frontend evoluiu com um modelo de dados próprio que está desalinhado do contrato.

### Agir

Integrar uma rota de ponta a ponta logo no início da Sprint 3, começando pela consulta do cardápio. Antes de criar telas novas.

---

## 6. Planejamento da próxima Sprint

### Meta da próxima Sprint

Permitir o cadastro de categorias, produtos, bairros e motoboys pela aplicação, com o frontend gravando e lendo os dados pela API, e registrar o primeiro feedback do cliente sobre as telas.

### Itens inicialmente selecionados

| User Story ou item | Responsável(is), se definido(s) | Resultado esperado |
| --- | --- | --- |
| Integração do cardápio com a API | Diego Silva e Lucas Sol | Telas de categorias, produtos e cardápio lendo e gravando pela API, sem dados no navegador |
| Alinhamento do contrato com as telas | Anna Hermes<br>e Diego Silva | Decisão registrada no contrato sobre combos, estoque por produto, imagem e ingredientes removíveis |
| Cadastro de bairros, taxas de entrega e motoboys | Gabriel Lessa<br>e Lucas Sol | API e tela de bairros com taxa e ativação. API de motoboys com nome e telefone, e a tela atual usando a API |
| Primeiro feedback do cliente | Gabriel Lessa | Feedback do cliente registrado no repositório e ajustes incluídos no backlog |

### Riscos ou impedimentos previstos

Deixar a integração front e backend no limite do tempo impossibilitando o feedback do cliente essencial pra Sprint.
