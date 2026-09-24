# Status Report da Sprint 1

## 1. Identificação

- **Projeto:** Komanda — sistema de gestão para lancheria com delivery (cliente: Mau Mau Lanches)
- **Número da Sprint:** 1
- **Período:** 17/09 a 24/09
- **Integrantes:** Anna Hermes, Diego Silva, Gabriel Lessa e Lucas Sol
- **Scrum Master da Sprint:** Gabriel Lessa

### Meta da Sprint

Definir as tecnologias e frameworks do sistema com base nas necessidades levantadas do projeto, com as escolhas documentadas e comprovadas pelos projetos base de backend e frontend executando nas máquinas da equipe.

---

## 2. Resultado da Sprint

### Situação da meta

- [x] Alcançada
- [ ] Parcialmente alcançada
- [ ] Não alcançada

### Resultado alcançado

O levantamento de requisitos com o cliente, a Mau Mau Lanches, foi concluído e documentado. Ele reúne 34 requisitos e 6 regras de negócio, cobrindo cardápio, pedidos com cálculo automático, estoque de insumos, acerto dos motoboys, fechamento de caixa e dashboard do gestor.

Com base nesses requisitos, a equipe definiu a stack: Node.js no backend e React 19 com Vite no frontend. O modelo de dados inicial foi elaborado com 12 entidades e o diagrama de relacionamento entre elas.

Os projetos base dos dois repositórios foram criados e executam localmente. O frontend já traz uma primeira versão das telas de pedido, cardápio, estoque e fechamento de motoboys, com dados fictícios.

### Principal dificuldade ou impedimento

Nenhum impedimento relevante.

---

## 3. Itens planejados e situação final

| User Story ou item | Responsável(is) | Situação final | Observação |
|---|---|---|---|
| Levantamento de requisitos com o cliente | Gabriel Lessa | Concluído | 34 requisitos e 6 regras de negócio documentados |
| Definição da stack de backend | Anna Hermes e Gabriel Lessa | Concluído | Node.js |
| Definição da stack de frontend | Diego Silva e Lucas Sol | Concluído | React 19 com Vite |
| Escolha do banco de dados e modelagem inicial das entidades | Lucas Sol e Anna Hermes | Concluído | 12 entidades modeladas com diagrama de relacionamento |
| Projeto base do backend executando | Anna Hermes | Concluído | Projeto base em Node.js executando localmente |
| Projeto base do frontend executando | Diego Silva e Lucas Sol | Concluído | Projeto base com primeira versão das telas |

---

## 4. Evidências e qualidade

### Evidências

- **Repositório de backend:** https://github.com/4nnahermes/komanda-backend
- **Repositório de frontend:** https://github.com/LucassolHenrique/Front-end_mau_mau_lanches
- **Quadro Kanban:** https://github.com/4nnahermes/komanda-backend/issues
- **Deploy ou instruções para executar o projeto:** instruções no README de cada repositório
- **Outras evidências, se necessárias:** [levantamento de requisitos](https://github.com/GabrielLTM/projeto-desenv/blob/main/Atividade%20Projeto%201/levantamento-requisitos.md), com requisitos, regras de negócio e modelo de entidades

### Checklist de qualidade

- [x] Os itens marcados como concluídos atendem aos critérios de aceite.
- [x] As funcionalidades entregues foram testadas pela equipe.
- [x] O código atualizado está no repositório oficial.
- [x] Os problemas conhecidos estão registrados no Kanban ou no repositório.

### Problemas conhecidos

O README do frontend indica clonar um repositório `komanda-frontend`, mas o repositório se chama `Front-end_mau_mau_lanches`, e os blocos de comando estão com a formatação quebrada. O modelo de entidades ainda é uma proposta inicial, e nomes e campos podem mudar ao longo da implementação.

---

## 5. Retrospectiva da Sprint

### Manter

Levantar os requisitos com o cliente antes de escolher as tecnologias deu uma base concreta para as decisões. O documento de requisitos, com exemplos reais da lancheria, já orienta as próximas sprints.

### Melhorar

Não houve nenhum ponto explícito que exija melhoria. A sprint cumpriu todas as entregas planejadas sem impedimentos.

### Agir

Definir o contrato da API logo no início da Sprint 2, antes da implementação, para que as duplas de backend e frontend trabalhem em paralelo sem esperar uma pela outra.

---

## 6. Planejamento da próxima Sprint

> Versão detalhada em `docs/planejamento/sprint-02.md`.

### Meta da próxima Sprint

Permitir que o atendente cadastre categorias e produtos e consulte o cardápio da Mau Mau Lanches pela aplicação, com o frontend em React consumindo a API em Node.js, e ter o design das telas do MVP validado em um primeiro feedback do cliente.

### Itens inicialmente selecionados

| User Story ou item | Responsável(is), se definido(s) | Resultado esperado |
|---|---|---|
| Contrato da API do MVP | Anna Hermes e Gabriel Lessa | Endpoints do MVP documentados, com o cardápio detalhado em requisição, resposta e erros |
| Design das telas do MVP | Diego Silva e Lucas Sol | Telas de pedido, cardápio, estoque e fechamento de motoboys navegáveis com dados fictícios |
| Banco de dados das entidades do cardápio | Lucas Sol, com apoio de Anna Hermes | Tabelas de categoria e produto criadas a partir do modelo de entidades |
| US01 – Cadastro de categorias | Anna Hermes e Diego Silva | Atendente cria, edita, desativa e ordena categorias pela aplicação |
| US02 – Cadastro de produtos | Gabriel Lessa e Lucas Sol | Atendente cadastra e edita produtos vinculados a uma categoria pela aplicação |
| US03 – Consulta do cardápio | Anna Hermes e Diego Silva | Aplicação exibe os produtos ativos agrupados por categoria, com preço |
| Primeiro feedback do cliente | Gabriel Lessa | Feedback do cliente sobre o design e o fluxo de cadastro registrado no repositório |

### Riscos ou impedimentos previstos

Mudanças no contrato da API durante a implementação podem quebrar a integração com o frontend, por isso toda alteração será combinada entre as duplas. O feedback do cliente pode pedir mudanças grandes no design.
