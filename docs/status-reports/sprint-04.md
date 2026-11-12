# Status Report da Sprint 4

## 1. Identificação

- **Projeto:** Komanda — sistema de gestão para lancheria com delivery (cliente: Mau Mau Lanches)
- **Número da Sprint:** 4
- **Período:** 22/10 a 05/11/2026
- **Integrantes:** Anna Hermes, Diego Silva, Gabriel Lessa e Lucas Sol
- **Scrum Master da Sprint:** a confirmar pela equipe

### Meta da Sprint

Validar com o cliente as funcionalidades entregues, aplicar os ajustes pedidos por ele e iniciar o registro de pedidos.

---

## 2. Resultado da Sprint

### Situação da meta

- [ ] Alcançada
- [ ] Parcialmente alcançada
- [x] Não alcançada

### Resultado alcançado

A equipe definiu os ajustes e o que falta para o registro de pedidos:

- Remover a tela de consulta do cardápio.
- Remover a saída de insumos do dashboard.
- No pedido, pedir o nome na retirada no balcão e o telefone na entrega.
- Ajustar a formatação do telefone do motoboy.
- Criar a API do pedido.

Nenhum item foi implementado.

### Principal dificuldade ou impedimento

Falta de organização e de priorização da equipe.

---

## 3. Itens planejados e situação final

| User Story ou item | Responsável(is) | Situação final | Observação |
|---|---|---|---|
| Apresentação e validação com o cliente | Equipe | Concluído | A conversa com o cliente gerou a lista de ajustes |
| Remover a tela de consulta do cardápio | A definir | Não iniciado | Pedido do cliente |
| Remover a saída de insumos do dashboard | A definir | Não iniciado | Pedido do cliente |
| Nome na retirada no balcão e telefone na entrega | A definir | Não iniciado | Pedido do cliente |
| Formatação do telefone do motoboy | A definir | Não iniciado | Pedido do cliente |
| API do pedido | A definir | Não iniciado | Primeira etapa do registro de pedidos |
| Validação dos cadastros com dados do restaurante | A definir | Não iniciado | Cardápio, bairros, taxas e motoboys ainda não conferidos com os dados reais |

---

## 4. Evidências e qualidade

### Evidências

- **Projeto:** [repositório do projeto](https://github.com/GabrielLTM/projeto-desenv).
- **Aplicação disponível online:** [acessar o Komanda](https://komanda-frontend.vercel.app).
- **Aplicação:** [repositório da aplicação](https://github.com/GabrielLTM/komanda-frontend).
- **Serviços do sistema:** [repositório dos serviços](https://github.com/GabrielLTM/komanda-backend).

### Checklist de qualidade

- [x] A apresentação ao cliente foi realizada e os ajustes foram levantados.
- [ ] Os ajustes pedidos pelo cliente foram implementados.
- [ ] A API do pedido foi criada.
- [ ] Os cadastros foram conferidos com os dados reais do restaurante.

### Problemas conhecidos

Os ajustes pedidos pelo cliente continuam pendentes.

---

## 5. Retrospectiva da Sprint

### Manter

Levar as funcionalidades ao cliente antes de avançar.

### Melhorar

Organização e priorização das tarefas da sprint.

### Agir

Criar uma issue com responsável para cada item no início da Sprint 5 e fazer os ajustes menores primeiro.

---

## 6. Planejamento da próxima Sprint

### Meta da próxima Sprint

Aplicar os ajustes definidos pela equipe e permitir que o atendente registre um pedido de retirada no balcão ou de entrega, com os dados salvos pela API.

### Itens inicialmente selecionados

| User Story ou item | Responsável(is), se definido(s) | Resultado esperado |
|---|---|---|
| Remover a tela de consulta do cardápio | A definir | A tela deixa de aparecer na aplicação |
| Remover a saída de insumos do dashboard | A definir | O dashboard deixa de exibir a saída de insumos |
| Formatação do telefone do motoboy | A definir | Telefone exibido e cadastrado no formato combinado com o cliente |
| API do pedido | A definir | Pedido registrado com itens, tipo de atendimento, total e forma de pagamento |
| Tela de pedido integrada à API | A definir | Pedido pede o nome na retirada no balcão e o telefone na entrega, e é salvo pela API |

### Riscos ou impedimentos previstos

O registro de pedidos é a parte mais complexa do sistema e pode não caber inteiro na sprint.
