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

A equipe conversou com o cliente sobre as funcionalidades entregues e levantou os ajustes que ele pediu e o que falta para o registro de pedidos:

- Remover a tela de consulta do cardápio.
- Remover a saída de insumos do dashboard.
- No pedido, pedir o nome do cliente quando for retirada no balcão e o telefone quando for entrega.
- Ajustar a formatação do telefone do motoboy.
- Criar a API do pedido.

Nenhum desses itens foi implementado durante a sprint.

### Principal dificuldade ou impedimento

A sprint foi dedicada ao levantamento com o cliente, e a implementação dos ajustes e do registro de pedidos não chegou a começar.

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

Os ajustes pedidos pelo cliente continuam pendentes. A aplicação ainda mostra a tela de consulta do cardápio e a saída de insumos no dashboard, e o telefone do motoboy segue com a formatação antiga.

---

## 5. Retrospectiva da Sprint

### Manter

Levar as funcionalidades entregues ao cliente antes de avançar. A conversa gerou ajustes concretos e definiu o que o registro de pedidos precisa pedir em cada tipo de atendimento.

### Melhorar

O levantamento terminou sem virar tarefas com responsável e prazo, e por isso a implementação não começou dentro da sprint.

### Agir

Transformar cada ajuste em uma issue com responsável e critério de aceite logo no início da Sprint 5, antes de qualquer outra atividade.

---

## 6. Planejamento da próxima Sprint

### Meta da próxima Sprint

Aplicar os ajustes pedidos pelo cliente e permitir que o atendente registre um pedido de retirada no balcão ou de entrega, com os dados salvos pela API.

### Itens inicialmente selecionados

| User Story ou item | Responsável(is), se definido(s) | Resultado esperado |
|---|---|---|
| Remover a tela de consulta do cardápio | A definir | A tela deixa de aparecer na aplicação |
| Remover a saída de insumos do dashboard | A definir | O dashboard deixa de exibir a saída de insumos |
| Formatação do telefone do motoboy | A definir | Telefone exibido e cadastrado no formato combinado com o cliente |
| API do pedido | A definir | Pedido registrado com itens, tipo de atendimento, total e forma de pagamento |
| Tela de pedido integrada à API | A definir | Pedido pede o nome na retirada no balcão e o telefone na entrega, e é salvo pela API |

### Riscos ou impedimentos previstos

O registro de pedidos é a parte mais complexa do sistema, porque envolve o cálculo do total, a taxa de entrega e o troco. Para caber na sprint, os ajustes menores devem ser feitos primeiro, e o pedido deve começar pelo fluxo mais simples, deixando a baixa de estoque para a sprint seguinte.
