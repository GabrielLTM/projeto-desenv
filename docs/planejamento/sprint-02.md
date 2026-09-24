# Planejamento da Sprint 2

## Identificação

- **Projeto:** Komanda — sistema de gestão para lancheria com delivery
- **Cliente:** Mau Mau Lanches
- **Sprint:** 2
- **Período:** 24/09 a 01/10
- **Integrantes:** Anna Hermes, Diego Silva, Gabriel Lessa e Lucas Sol
- **Scrum Master da Sprint:** Gabriel Lessa *(ajustar se a equipe decidir outro)*

---

## Ponto de partida

A Sprint 1 entregou a base para começar a implementação:

- **Requisitos** levantados com o cliente: 34 requisitos e 6 regras de negócio, cobrindo cardápio, pedidos, estoque, motoboys, fechamento de caixa e dashboard.
- **Entidades** do modelo de dados definidas, de categoria e produto até pedido, bairro e motoboy.
- **Stack** escolhida: Node.js no backend e React no frontend.

---

## Meta da Sprint

> Permitir que o atendente cadastre categorias e produtos e consulte o cardápio da Mau Mau Lanches pela aplicação, com o frontend em React consumindo a API em Node.js, e ter o design das telas do MVP validado em um primeiro feedback do cliente.

**Por que começar pelo cardápio.** Pedidos, baixa de estoque e fechamento de caixa dependem de categorias e produtos cadastrados. O cardápio é a primeira fatia do MVP que funciona sozinha e que o cliente consegue avaliar.

**Por que buscar feedback agora.** Validar o design antes de implementar pedidos e estoque evita retrabalho nas telas mais complexas do sistema.

---

## Estrutura dos repositórios

| Repositório | Responsáveis | Stack |
|---|---|---|
| Backend | Anna Hermes e Gabriel Lessa | Node.js |
| Frontend | Diego Silva e Lucas Sol | React 19 e Vite |

Lucas Sol também apoia a modelagem e a estrutura do banco de dados, junto à dupla de backend.

---

## Itens selecionados

| # | Item | Responsável(is) | Resultado esperado |
|---|---|---|---|
| 1 | Contrato da API do MVP | Anna Hermes e Gabriel Lessa | Endpoints do MVP documentados, com o cardápio detalhado em requisição, resposta e erros |
| 2 | Design das telas do MVP | Diego Silva e Lucas Sol | Telas de pedido, cardápio, estoque e fechamento de motoboys navegáveis com dados fictícios |
| 3 | Banco de dados das entidades do cardápio | Lucas Sol, com apoio de Anna Hermes | Tabelas de categoria e produto criadas a partir do modelo de entidades da Sprint 1 |
| 4 | US01 – Cadastro de categorias | Anna Hermes (API) e Diego Silva (tela) | Atendente cria, edita, desativa e ordena categorias pela aplicação |
| 5 | US02 – Cadastro de produtos | Gabriel Lessa (API) e Lucas Sol (tela) | Atendente cadastra e edita produtos vinculados a uma categoria pela aplicação |
| 6 | US03 – Consulta do cardápio | Anna Hermes (API) e Diego Silva (tela) | Aplicação exibe os produtos ativos agrupados por categoria, com preço |
| 7 | Primeiro feedback do cliente | Gabriel Lessa | Feedback do cliente sobre o design e o fluxo de cadastro registrado no repositório |

As User Stories correspondem aos requisitos 1, 4 e 8 do levantamento. A distribuição é uma organização inicial e pode ser ajustada durante a sprint.

---

## Critérios de aceite

**1. Contrato da API do MVP**

- Os endpoints de cardápio, pedidos, estoque, motoboys e fechamento estão listados com método e rota.
- Os endpoints de categoria e produto têm formato de requisição, resposta e erros definidos.
- O contrato está versionado no repositório de backend e foi revisado pela dupla de frontend.

**2. Design das telas do MVP**

- As telas de pedido, cardápio, estoque e fechamento de motoboys estão navegáveis.
- As telas seguem os campos e fluxos do levantamento de requisitos.
- O design foi apresentado aos quatro integrantes antes da sessão com o cliente.

**3. Banco de dados das entidades do cardápio**

- As tabelas de categoria e produto existem com os campos definidos na Sprint 1.
- A estrutura do banco é criada por script versionado, e não manualmente.

**4. US01 – Cadastro de categorias**

> Como atendente, quero cadastrar e organizar as categorias do cardápio, para agrupar os produtos como o cliente vê no balcão.

- É possível criar, editar e desativar uma categoria pela tela.
- É possível definir a ordem de exibição das categorias.
- O sistema rejeita categoria sem nome, com mensagem clara.

**5. US02 – Cadastro de produtos**

> Como atendente, quero cadastrar os produtos com preço e categoria, para montar o cardápio que será usado nos pedidos.

- É possível cadastrar produto com nome, categoria, descrição, preço e situação ativa ou inativa.
- O sistema rejeita produto sem nome, sem categoria ou com preço negativo.
- A edição de um produto persiste as alterações.

**6. US03 – Consulta do cardápio**

> Como atendente, quero ver o cardápio organizado por categoria, para encontrar rápido o produto que o cliente pediu.

- A tela lista apenas produtos ativos, agrupados por categoria, na ordem definida.
- Cada produto aparece com nome e preço.
- Produto desativado deixa de aparecer sem precisar ser excluído.

**7. Primeiro feedback do cliente**

- O cliente viu as telas do MVP e o fluxo de cadastro funcionando.
- Os pontos levantados pelo cliente estão registrados no repositório.
- Os ajustes pedidos foram incluídos no backlog, com prioridade definida pela equipe.

---

## Ordem de execução

1. **Contrato da API** abre a sprint, para que as duas duplas trabalhem sobre a mesma definição.
2. **Design das telas** e **banco de dados** avançam em paralelo, cada um na sua frente.
3. **US01, US02 e US03** são implementadas de ponta a ponta, API e tela juntas.
4. **Feedback do cliente** acontece na metade da sprint, com o design pronto e pelo menos o cadastro de categorias funcionando.
5. **Ajustes do feedback** que couberem na sprint entram antes do encerramento; os maiores vão para a Sprint 3.

---

## Organização do trabalho

- Cada User Story tem uma pessoa na API e uma na tela, o que obriga backend e frontend a integrar desde o primeiro item.
- Os integrantes de uma dupla testam o que a outra implementou, fazendo o conhecimento circular entre as frentes.
- Todos os integrantes realizam commits durante a sprint.
- O quadro Kanban é atualizado no início da sprint com os itens e as tarefas derivadas.
- Impedimentos são comunicados ao grupo assim que aparecem, sem esperar a próxima aula.

---

## Definição de pronto

Um item só é considerado concluído quando:

- atende a todos os seus critérios de aceite;
- foi testado por pelo menos um integrante que não o implementou;
- está versionado no repositório oficial correspondente.

---

## Riscos e mitigações

| Risco | Impacto | Mitigação |
|---|---|---|
| Mudanças no contrato durante a implementação | Quebra a integração entre frontend e backend | Toda mudança é combinada entre as duplas e registrada no repositório |
| Feedback do cliente pedir mudanças grandes | Retrabalho no design e nas telas já implementadas | Sessão na metade da sprint; ajustes grandes vão para o backlog da Sprint 3 |
| Problemas de integração entre as aplicações | Atraso nas três User Stories | Integrar um endpoint simples logo no início da sprint |
| Escopo grande do MVP | Sprint termina com várias frentes pela metade | Manter a meta restrita a categorias, produtos e consulta do cardápio |
