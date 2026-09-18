# Status Report da Sprint 1

## 1. Identificação

- **Projeto:** Komanda — sistema de gestão para restaurantes
- **Número da Sprint:** 1
- **Período:** 17/09 a 24/09 *(ajustar conforme o calendário da disciplina)*
- **Integrantes:** Anna Hermes, Diego Silva, Gabriel Lessa e Lucas Sol
- **Scrum Master da Sprint:** Gabriel Lessa *(ajustar se a equipe decidir outro)*

### Meta da Sprint

**Meta:**

Definir as tecnologias e frameworks do sistema com base nas necessidades levantadas do projeto, com as escolhas documentadas e comprovadas pelos projetos base de backend e frontend executando nas máquinas da equipe.

---

## 2. Resultado da Sprint

### Situação da meta

- [ ] Alcançada
- [ ] Parcialmente alcançada
- [ ] Não alcançada

> Preencher somente no encerramento da Sprint 1.

### Resultado alcançado

**Resultado:**

> Preencher somente no encerramento da Sprint 1.

### Principal dificuldade ou impedimento

**Dificuldade ou impedimento:**

> Preencher somente no encerramento da Sprint 1.

---

## 3. Itens planejados e situação final

| User Story ou item | Responsável(is) | Situação final | Observação |
|---|---|---|---|
| Levantamento de requisitos com o cliente | Gabriel Lessa |  |  |
| Definição da stack de backend | Anna Hermes e Gabriel Lessa |  |  |
| Definição da stack de frontend | Diego Silva e Lucas Sol |  |  |
| Escolha do banco de dados e modelagem inicial das entidades | Lucas Sol e Anna Hermes |  |  |
| Projeto base do backend executando | Anna Hermes |  |  |
| Projeto base do frontend executando | Diego Silva e Lucas Sol |  |  |

> Situação final preenchida somente no encerramento da Sprint 1.

---

## 4. Evidências e qualidade

### Evidências

- **Repositório de backend (`komanda-backend`):**
- **Repositório de frontend (`komanda-frontend`):**
- **Quadro Kanban:**
- **Deploy ou instruções para executar o projeto:**
- **Outras evidências, se necessárias:**

> Preencher somente no encerramento da Sprint 1.

### Checklist de qualidade

- [ ] Os itens marcados como concluídos atendem aos critérios de aceite.
- [ ] As funcionalidades entregues foram testadas pela equipe.
- [ ] O código atualizado está no repositório oficial.
- [ ] Os problemas conhecidos estão registrados no Kanban ou no repositório.

> Preencher somente no encerramento da Sprint 1.

### Problemas conhecidos

**Registro:**

> Preencher somente no encerramento da Sprint 1.

---

## 5. Retrospectiva da Sprint

### Manter

**Registro:**

> Preencher somente no encerramento da Sprint 1.

### Melhorar

**Registro:**

> Preencher somente no encerramento da Sprint 1.

### Agir

**Ação:**

> Preencher somente no encerramento da Sprint 1.

---

## 6. Planejamento da Sprint 1

> Seção utilizada como planejamento inicial da Sprint 1, conforme orientação da atividade.
> Versão detalhada em `docs/planejamento/sprint-01.md`.

### Meta da Sprint

**Meta:**

Definir as tecnologias e frameworks do sistema com base nas necessidades levantadas do projeto, com as escolhas documentadas e comprovadas pelos projetos base de backend e frontend executando nas máquinas da equipe.

A escolha tecnológica vem depois do levantamento de requisitos com o cliente, e não antes: são as necessidades de cardápio, vendas, produtos e estoque que definem o que a stack precisa suportar. O sistema será dividido em dois repositórios, `komanda-backend` e `komanda-frontend`.

### Itens inicialmente selecionados

| User Story ou item | Responsável(is) | Resultado esperado |
|---|---|---|
| Levantamento de requisitos com o cliente | Gabriel Lessa | Requisitos funcionais e não funcionais do MVP registrados, servindo de base para as escolhas tecnológicas |
| Definição da stack de backend | Anna Hermes e Gabriel Lessa | Linguagem e framework de backend escolhidos e documentados, avaliados contra os requisitos levantados |
| Definição da stack de frontend | Diego Silva e Lucas Sol | Linguagem e framework de frontend escolhidos e documentados, avaliados contra os requisitos levantados |
| Escolha do banco de dados e modelagem inicial das entidades | Lucas Sol, com apoio de Anna Hermes | Banco escolhido e modelo inicial de produto, cardápio, estoque e venda com seus relacionamentos |
| Projeto base do backend executando | Anna Hermes | Repositório de backend criado e projeto base rodando localmente, com instruções no README |
| Projeto base do frontend executando | Diego Silva e Lucas Sol | Repositório de frontend criado e projeto base rodando localmente, com instruções no README |

> Organização desta sprint. A equipe poderá ajustar a distribuição do trabalho durante o andamento.

### Critérios de aceite

**Levantamento de requisitos com o cliente**

- Os requisitos funcionais e não funcionais estão registrados em arquivo versionado.
- Os requisitos cobrem os quatro módulos do MVP: cardápio, produtos, vendas e estoque.
- O cliente confirmou a lista de requisitos levantados.

**Definição da stack de backend**

- Pelo menos duas alternativas foram avaliadas para linguagem e framework.
- A comparação usa critérios explícitos, incluindo os requisitos levantados e a experiência prévia da equipe.
- A escolha está documentada com justificativa e foi apresentada aos quatro integrantes.

**Definição da stack de frontend**

- Pelo menos duas alternativas foram avaliadas para linguagem e framework.
- A escolha considera a integração com a API definida pela dupla de backend.
- A escolha está documentada com justificativa e foi apresentada aos quatro integrantes.

**Escolha do banco de dados e modelagem inicial das entidades**

- O banco de dados está escolhido e justificado frente aos requisitos levantados.
- O modelo contempla produto, cardápio, estoque e venda, com os relacionamentos entre eles.
- O modelo está versionado no repositório de backend.

**Projeto base do backend executando**

- O repositório de backend existe e os quatro integrantes têm acesso.
- O projeto base sobe localmente e responde a uma requisição de verificação.
- O README traz as instruções de execução, validadas por um integrante de fora da dupla de backend.

**Projeto base do frontend executando**

- O repositório de frontend existe e os quatro integrantes têm acesso.
- O projeto base sobe localmente e exibe uma tela inicial.
- O README traz as instruções de execução, validadas por um integrante de fora da dupla de frontend.

### Organização inicial do trabalho

- O levantamento de requisitos abre a sprint, porque todas as escolhas tecnológicas dependem dele.
- As stacks de backend e frontend são definidas em paralelo, cada dupla na sua frente, com alinhamento do contrato da API entre elas.
- A divisão por frentes vale para esta sprint, em que o objetivo é decidir a stack de cada lado do sistema. Não é permanente: nas próximas sprints a equipe fará rodízio entre backend e frontend.
- A validação do README de cada projeto base é feita por um integrante da outra dupla, garantindo que o conhecimento circule.
- Todos os integrantes realizam commits durante a sprint.
- O quadro Kanban é atualizado no início da sprint com os itens e as tarefas derivadas.

### Definição de pronto

Um item só é considerado concluído quando atende a todos os seus critérios de aceite, foi verificado por pelo menos um integrante que não o executou e está versionado no repositório oficial correspondente.

### Riscos ou impedimentos previstos

- **Indisponibilidade do cliente para o levantamento.** Trava o primeiro item e atrasa as decisões de stack das duas duplas. Mitigação: agendar a conversa no início da sprint e, se necessário, seguir com premissas registradas, ajustando depois.
- **Duplas decidirem stacks incompatíveis entre si.** Gera retrabalho na integração entre frontend e backend. Mitigação: alinhar o contrato da API entre as duplas antes de fechar as escolhas.
- **Indecisão na escolha das tecnologias.** Consome a sprint sem fechar a meta. Mitigação: definir prazo limite para a decisão e priorizar tecnologia que a dupla já conhece.
- **Conhecimento concentrado em cada dupla.** Gera dependência de pessoas específicas nas próximas sprints. Mitigação: apresentação cruzada dos projetos base e validação do README pela outra dupla.
- **Diferenças de ambiente entre as máquinas.** Nem todos conseguem executar os projetos base. Mitigação: documentar a configuração no README e validar em todas as máquinas ainda dentro da sprint.
