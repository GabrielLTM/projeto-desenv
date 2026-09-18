# Status Report da Sprint 0

## 1. Identificação

- **Projeto:** Komanda — sistema de gestão para restaurantes
- **Número da Sprint:** 0
- **Período:** [preencher com as datas reais desta sprint]
- **Integrantes:** Anna Hermes, Diego Silva, Gabriel Lessa e Lucas Sol
- **Scrum Master da Sprint:** [a definir pela equipe]

### Meta da Sprint

**Meta:**

Compreender, por meio do processo de Design Thinking, o problema enfrentado por pequenos empresários do setor alimentício e definir a proposta de valor do sistema a ser desenvolvido.

---

## 2. Resultado da Sprint

### Situação da meta

- [x] Alcançada
- [ ] Parcialmente alcançada
- [ ] Não alcançada

### Resultado alcançado

**Resultado:**

A equipe definiu a persona (empresário de lanchonete, entre 35 e 65 anos, pouco familiarizado com tecnologia, que controla vendas e estoque manualmente) e o problema central: como ajudar esse público a controlar vendas e estoque do dia a dia sem depender de anotações em papel.

Foi realizada uma sessão de ideação com seis ideias candidatas, da qual resultou a ideia vencedora: um sistema de venda e estoque para restaurante. A proposta de valor foi formalizada como um sistema simples de gestão de vendas e estoque, com controle mínimo de insumos, voltado a pequenos negócios pouco adeptos à tecnologia — em contraste com planilhas complexas ou sistemas de gestão robustos voltados a grandes negócios. Esse trabalho foi consolidado na apresentação "Design Thinking: do Problema à Proposta de Valor", entregue como Atividade 1.

Nenhum código ou artefato técnico do sistema foi iniciado nesta sprint.

### Principal dificuldade ou impedimento

**Dificuldade ou impedimento:**

Convergir entre as diversas ideias levantadas pelo grupo (gestão de estoque, calculadora para ceramista, sistema para relojoaria, extrator de pedidos no WhatsApp, organização de casa e caronas para alunos) até chegar a uma única proposta priorizada.

---

## 3. Itens planejados e situação final

| User Story ou item | Responsável(is) | Situação final | Observação |
|---|---|---|---|
| Definir persona e problema | Equipe | Concluído | Registrado na apresentação de Design Thinking |
| Gerar e priorizar ideias (ideação) | Equipe | Concluído | 6 ideias levantadas; 1 selecionada |
| Definir proposta de valor | Equipe | Concluído | Proposta de valor documentada |

---

## 4. Evidências e qualidade

### Evidências

- **Repositório:** [ainda não criado]
- **Quadro Kanban:** [ainda não criado]
- **Deploy ou instruções para executar o projeto:** não se aplica nesta sprint (nenhum código foi desenvolvido)
- **Outras evidências, se necessárias:** Apresentação "Design Thinking: do Problema à Proposta de Valor" (Atividade 1)

### Checklist de qualidade

- [ ] Os itens marcados como concluídos atendem aos critérios de aceite.
- [ ] As funcionalidades entregues foram testadas pela equipe.
- [ ] O código atualizado está no repositório oficial.
- [ ] Os problemas conhecidos estão registrados no Kanban ou no repositório.

> Itens não marcados porque esta sprint não envolveu desenvolvimento de código nem repositório/kanban ainda ativos.

### Problemas conhecidos

**Registro:**

O repositório de código e o quadro Kanban do projeto ainda não foram criados. A stack tecnológica do backend ainda não foi escolhida. Nenhuma linha de código foi escrita até o momento.

---

## 5. Retrospectiva da Sprint

### Manter

**Registro:**

O uso do processo de Design Thinking antes de partir para o desenvolvimento ajudou a equipe a alinhar uma visão clara e compartilhada do problema e do público-alvo.

### Melhorar

**Registro:**

Definir mais cedo as ferramentas de apoio ao projeto (repositório de código, quadro Kanban, papéis da equipe) para não atrasar o início da Sprint 1.

### Agir

**Ação:**

Criar o repositório do projeto e o quadro Kanban, e definir a stack tecnológica do backend, logo no início da Sprint 1, antes de iniciar a implementação.

---

## 6. Planejamento da próxima Sprint

### Meta da próxima Sprint

**Meta:**

Definir as tecnologias e frameworks do sistema com base nas necessidades levantadas do projeto, com as escolhas documentadas e comprovadas pelos projetos base de backend e frontend executando nas máquinas da equipe.

### Itens inicialmente selecionados

| User Story ou item | Responsável(is), se definido(s) | Resultado esperado |
|---|---|---|
| Levantamento de requisitos com o cliente | Gabriel Lessa | Requisitos funcionais e não funcionais do MVP registrados |
| Definição da stack de backend | Anna Hermes e Gabriel Lessa | Linguagem e framework de backend escolhidos e documentados |
| Definição da stack de frontend | Diego Silva e Lucas Sol | Linguagem e framework de frontend escolhidos e documentados |
| Escolha do banco de dados e modelagem inicial das entidades | Lucas Sol, com apoio de Anna Hermes | Banco escolhido e modelo inicial de produto, cardápio, estoque e venda |
| Projeto base do backend executando | Anna Hermes | Repositório `komanda-backend` criado e projeto base rodando localmente |
| Projeto base do frontend executando | Diego Silva e Lucas Sol | Repositório `komanda-frontend` criado e projeto base rodando localmente |

> Seleção inicial; detalhada no planejamento da Sprint 1 em `docs/planejamento/sprint-01.md`.

### Riscos ou impedimentos previstos

**Riscos:**

A disponibilidade do cliente para o levantamento de requisitos pode atrasar as decisões tecnológicas, que dependem dele. As duas duplas podem escolher stacks incompatíveis entre si, gerando retrabalho na integração. A falta de experiência prévia da equipe com alguma das tecnologias escolhidas pode impedir que os projetos base subam dentro da sprint.
