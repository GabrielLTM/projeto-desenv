# Planejamento da Sprint 1

## Identificação

- **Projeto:** Komanda — sistema de gestão para restaurantes
- **Sprint:** 1
- **Período:** 17/09 a 24/09 *(ajustar conforme o calendário da disciplina)*
- **Integrantes:** Anna Hermes, Diego Silva, Gabriel Lessa e Lucas Sol
- **Scrum Master da Sprint:** Gabriel Lessa *(ajustar se a equipe decidir outro)*

---

## Contexto do projeto

**Persona.** Empresário de lanchonete, entre 35 e 65 anos, que controla vendas e estoque manualmente e tem dificuldade de se adaptar a novas tecnologias.

**Problema.** Como ajudar pequenos empresários do setor alimentício, pouco familiarizados com tecnologia, a controlar vendas e estoque do dia a dia sem depender de anotações em papel?

**Proposta de valor.** Um sistema simples de registro de vendas e insumos essenciais, em contraste com planilhas complexas ou sistemas de gestão robustos voltados a grandes negócios.

**Nome.** Komanda, referência à comanda usada no dia a dia do restaurante, o papel que o sistema substitui.

**Escopo do produto.** Sistema de gestão de restaurante cobrindo cardápio, produtos, vendas e estoque, dividido em dois repositórios: um backend genérico e um frontend que o consome.

---

## Meta da Sprint

> Definir as tecnologias e frameworks do sistema com base nas necessidades levantadas do projeto, com as escolhas documentadas e comprovadas pelos projetos base de backend e frontend executando nas máquinas da equipe.

**Por que esta meta.** A escolha tecnológica precisa vir depois do levantamento de requisitos com o cliente, e não antes: são as necessidades de cardápio, vendas, produtos e estoque que definem o que a stack precisa suportar. Ao final da sprint a equipe terá a base técnica dos dois repositórios pronta para começar a implementar as funcionalidades do MVP na Sprint 2.

---

## Estrutura dos repositórios

O sistema será dividido em dois repositórios independentes:

| Repositório | Responsáveis | Conteúdo |
|---|---|---|
| `komanda-backend` | Anna Hermes e Gabriel Lessa | API de gestão de cardápio, produtos, vendas e estoque |
| `komanda-frontend` | Diego Silva e Lucas Sol | Interface que consome a API do backend |

Lucas Sol também dá apoio na modelagem e na escolha do banco de dados, junto à dupla de backend.

---

## Itens selecionados

| # | Item | Responsável(is) | Resultado esperado |
|---|---|---|---|
| 1 | Levantamento de requisitos com o cliente | Gabriel Lessa | Requisitos funcionais e não funcionais do MVP registrados, servindo de base para as escolhas tecnológicas |
| 2 | Definição da stack de backend | Anna Hermes e Gabriel Lessa | Linguagem e framework de backend escolhidos e documentados, avaliados contra os requisitos levantados |
| 3 | Definição da stack de frontend | Diego Silva e Lucas Sol | Linguagem e framework de frontend escolhidos e documentados, avaliados contra os requisitos levantados |
| 4 | Escolha do banco de dados e modelagem inicial das entidades | Lucas Sol, com apoio de Anna Hermes | Banco escolhido e modelo inicial de produto, cardápio, estoque e venda com seus relacionamentos |
| 5 | Projeto base do backend executando | Anna Hermes | Repositório de backend criado e projeto base rodando localmente, com instruções no README |
| 6 | Projeto base do frontend executando | Diego Silva e Lucas Sol | Repositório de frontend criado e projeto base rodando localmente, com instruções no README |

A distribuição é a organização desta sprint e pode ser ajustada pela equipe durante o andamento.

---

## Critérios de aceite

**1. Levantamento de requisitos com o cliente**

- Os requisitos funcionais e não funcionais estão registrados em arquivo versionado.
- Os requisitos cobrem os quatro módulos do MVP: cardápio, produtos, vendas e estoque.
- O cliente confirmou a lista de requisitos levantados.

**2. Definição da stack de backend**

- Pelo menos duas alternativas foram avaliadas para linguagem e framework.
- A comparação usa critérios explícitos, incluindo os requisitos levantados e a experiência prévia da equipe.
- A escolha está documentada com justificativa e foi apresentada aos quatro integrantes.

**3. Definição da stack de frontend**

- Pelo menos duas alternativas foram avaliadas para linguagem e framework.
- A escolha considera a integração com a API definida pela dupla de backend.
- A escolha está documentada com justificativa e foi apresentada aos quatro integrantes.

**4. Escolha do banco de dados e modelagem inicial das entidades**

- O banco de dados está escolhido e justificado frente aos requisitos levantados.
- O modelo contempla produto, cardápio, estoque e venda, com os relacionamentos entre eles.
- O modelo está versionado no repositório de backend.

**5. Projeto base do backend executando**

- O repositório de backend existe e os quatro integrantes têm acesso.
- O projeto base sobe localmente e responde a uma requisição de verificação.
- O README traz as instruções de execução, validadas por um integrante de fora da dupla de backend.

**6. Projeto base do frontend executando**

- O repositório de frontend existe e os quatro integrantes têm acesso.
- O projeto base sobe localmente e exibe uma tela inicial.
- O README traz as instruções de execução, validadas por um integrante de fora da dupla de frontend.

---

## Ordem de execução

A sprint tem dependência entre os itens, e a ordem importa:

1. **Requisitos com o cliente** abrem a sprint, porque todas as escolhas tecnológicas dependem deles.
2. **Stack de backend** e **stack de frontend** são definidas em paralelo, cada dupla na sua frente.
3. **Banco de dados e modelagem** acompanham a definição do backend.
4. **Projetos base** só podem subir depois das respectivas decisões de stack.

---

## Organização do trabalho

- A divisão por frentes vale para esta sprint, em que o objetivo é justamente decidir a stack de cada lado do sistema. Ela não é permanente.
- Ao final da sprint, cada dupla apresenta à outra a stack escolhida e o projeto base, para que todos consigam rodar os dois repositórios.
- A validação do README de cada projeto base é feita por um integrante da outra dupla, garantindo que o conhecimento circule.
- Nas próximas sprints a equipe fará rodízio entre backend e frontend, evitando divisão rígida e permanente.
- Todos os integrantes realizam commits durante a sprint.
- O quadro Kanban é atualizado no início da sprint com os itens e as tarefas derivadas.
- Impedimentos são comunicados ao grupo assim que aparecem, sem esperar a próxima aula.

---

## Definição de pronto

Um item só é considerado concluído quando:

- atende a todos os seus critérios de aceite;
- foi verificado por pelo menos um integrante que não o executou;
- está versionado no repositório oficial correspondente.

---

## Riscos e mitigações

| Risco | Impacto | Mitigação |
|---|---|---|
| Indisponibilidade do cliente para o levantamento | Trava o primeiro item e atrasa as decisões de stack das duas duplas | Agendar a conversa no início da sprint; se necessário, seguir com premissas registradas e ajustar depois |
| Duplas decidirem stacks incompatíveis entre si | Retrabalho na integração entre frontend e backend | Alinhar o contrato da API entre as duplas antes de fechar as escolhas |
| Indecisão na escolha das tecnologias | Consome a sprint sem fechar a meta | Definir prazo limite para a decisão e priorizar tecnologia que a dupla já conhece |
| Conhecimento concentrado em cada dupla | Dependência de pessoas específicas nas próximas sprints | Apresentação cruzada dos projetos base e validação do README pela outra dupla |
| Diferenças de ambiente entre as máquinas | Nem todos conseguem executar os projetos base | Documentar a configuração no README e validar em todas as máquinas ainda dentro da sprint |
