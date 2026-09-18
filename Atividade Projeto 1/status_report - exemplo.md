# Status Report da Sprint 1

## 1. Identificação

- **Projeto:** TaskFlow
- **Número da Sprint:** 1
- **Período:** 17/09 a 24/09
- **Integrantes:** Ana, Bruno, Carlos e Daniela
- **Scrum Master da Sprint:** Bruno

### Meta da Sprint

> Informe a meta definida no planejamento da sprint que está sendo finalizada.

**Meta:**

Permitir que um usuário realize seu cadastro e acesse o sistema.

---

## 2. Resultado da Sprint

### Situação da meta

- [ ] Alcançada
- [x] Parcialmente alcançada
- [ ] Não alcançada

### Resultado alcançado

> Descreva brevemente quais funcionalidades ou resultados foram concluídos e estão funcionando ao final da sprint.

**Resultado:**

O cadastro de usuários foi concluído. A aplicação permite preencher os dados,
validar os campos obrigatórios e salvar as informações no banco de dados.

A interface de login também foi implementada, mas a autenticação ainda não
está integrada ao backend.

### Principal dificuldade ou impedimento

> Informe somente a dificuldade ou o impedimento que mais afetou a sprint. Caso não tenha ocorrido, escreva “Nenhum impedimento relevante”.

**Dificuldade ou impedimento:**

A equipe encontrou dificuldades na configuração da autenticação e na integração
entre frontend e backend.

---

## 3. Itens planejados e situação final

**Utilize apenas os seguintes status:**

- Concluído
- Em andamento
- Não iniciado
- Bloqueado

| User Story ou item | Responsável(is) | Situação final | Observação |
|---|---|---|---|
| US01 – Cadastro de usuário | Ana e Carlos | Concluído | Critérios de aceite verificados |
| US02 – Login de usuário | Bruno e Daniela | Em andamento | Interface concluída; autenticação pendente |
| Configuração inicial do projeto | Equipe | Concluído | Repositório e ambientes configurados |

> Inclua somente as User Stories ou os itens principais planejados para a sprint.  
> Não copie todas as tarefas menores do quadro Kanban.

---

## 4. Evidências e qualidade

### Evidências

- **Repositório:** https://github.com/exemplo/taskflow
- **Quadro Kanban:** https://github.com/exemplo/taskflow/projects
- **Deploy ou instruções para executar o projeto:** instruções disponíveis no README
- **Outras evidências, se necessárias:** GIF do cadastro disponível em `docs/evidencias`

### Checklist de qualidade

- [x] Os itens marcados como concluídos atendem aos critérios de aceite.
- [x] As funcionalidades entregues foram testadas pela equipe.
- [x] O código atualizado está no repositório oficial.
- [x] Os problemas conhecidos estão registrados no Kanban ou no repositório.

### Problemas conhecidos

> Informe os problemas que permanecem no incremento. Caso não tenham sido identificados, escreva “Nenhum problema conhecido”.

**Registro:**

A autenticação ainda não está integrada ao frontend. A mensagem apresentada
quando o usuário informa um e-mail já cadastrado também precisa ser melhorada.

---

## 5. Retrospectiva da Sprint

### Manter

> O que funcionou bem e deve continuar?

**Registro:**

O trabalho em pares facilitou a integração entre frontend e backend.

### Melhorar

> O que precisa mudar na próxima sprint?

**Registro:**

A equipe precisa avaliar as dependências técnicas antes de iniciar uma
User Story.

### Agir

> Qual ação concreta a equipe adotará na próxima sprint?

**Ação:**

Realizar uma verificação técnica das integrações no meio da próxima sprint.

---

## 6. Planejamento da próxima Sprint

### Meta da próxima Sprint

> Escreva um resultado claro e verificável que a equipe pretende alcançar.

**Meta:**

Permitir que o usuário faça login e acesse a área autenticada do sistema.

### Itens inicialmente selecionados

| User Story ou item | Responsável(is), se definido(s) | Resultado esperado |
|---|---|---|
| US02 – Login de usuário | Bruno e Daniela | Login integrado ao backend |
| US03 – Área autenticada | Ana e Carlos | Usuário autenticado visualiza a página inicial |
| Melhorar mensagem de e-mail duplicado | Carlos | Mensagem clara para o usuário |

> Esta é uma seleção inicial. O planejamento poderá ser ajustado pela equipe no início da próxima sprint.

### Riscos ou impedimentos previstos

> Informe os principais fatores que podem dificultar o cumprimento da próxima meta. Caso nenhum risco tenha sido identificado, escreva “Nenhum risco identificado”.

**Riscos:**

A equipe ainda precisa compreender melhor a biblioteca de autenticação utilizada.
Se a dificuldade continuar, será necessário simplificar a solução ou solicitar
orientação técnica.