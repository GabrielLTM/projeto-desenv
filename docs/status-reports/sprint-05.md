# Status Report da Sprint 5

## 1. Identificação

- **Projeto:** Komanda — sistema de gestão para lancheria com delivery (cliente: Mau Mau Lanches)
- **Número da Sprint:** 5
- **Período:** 05/11 a 19/11/2026
- **Integrantes:** Anna Hermes, Diego Silva, Gabriel Lessa e Lucas Sol

### Meta da Sprint

Aplicar os ajustes definidos pela equipe e permitir que o atendente registre um pedido de retirada no balcão ou de entrega, com os dados salvos pela API.

---

## 2. Resultado da Sprint

### Situação da meta

- [x] Alcançada
- [ ] Parcialmente alcançada
- [ ] Não alcançada

### Resultado alcançado

Os ajustes definidos pela equipe foram aplicados e publicados:

- A tela de consulta do cardápio foi removida.
- A saída de insumos foi removida do caixa.
- O telefone do motoboy passou a ser formatado no cadastro e na listagem.

A API de pedidos foi criada. Ela registra pedidos de balcão e de entrega, calcula subtotal, taxa de entrega, total e troco, e controla o status e o motoboy de cada pedido.

A tela de pedido foi integrada à API. Ela pede o nome do cliente e mostra o telefone só na entrega, e o quadro de pedidos grava o status e o motoboy na API. O fluxo completo foi testado de ponta a ponta.

Além do planejado, foi criada a API do dashboard e do fechamento de caixa, com as métricas do período e o acerto dos motoboys, e a tela de caixa passou a usar essa API. O fiado fica fora das métricas pois no fluxo do cliente o fiado é algo que não é recebido posteriormente.

O cardápio real da Mau Mau foi cadastrado no banco publicado.

### Principal dificuldade ou impedimento

Nenhum impedimento relevante.

---

## 3. Itens planejados e situação final

| User Story ou item | Responsável(is) | Situação final | Observação |
|---|---|---|---|
| Remover a tela de consulta do cardápio | Diego Silva | Concluído | Publicado |
| Remover a saída de insumos do dashboard | Lucas Sol | Concluído | Publicado |
| Formatação do telefone do motoboy | Anna Hermes | Concluído | Publicado |
| API do pedido | Anna Hermes | Concluído | Presente no repositório |
| Tela de pedido integrada à API | Gabriel Lessa | Concluído | Grava e lê os pedidos pela API |
| API do dashboard e do fechamento de caixa | Gabriel Lessa | Concluído | O fiado fica fora das métricas |
| Tela de caixa integrada à API | Gabriel Lessa | Concluído | Métricas e acerto dos motoboys vêm da API |

---

## 4. Evidências e qualidade

### Evidências

- **Projeto:** [repositório do projeto](https://github.com/GabrielLTM/projeto-desenv).
- **Aplicação disponível online:** [acessar o Komanda](https://komanda-frontend.vercel.app).
- **Frontend:** [repositório do frontend](https://github.com/GabrielLTM/komanda-frontend).
- **Backend:** [repositório do backend](https://github.com/4nnahermes/komanda-backend).

### Checklist de qualidade

- [x] Os ajustes definidos pela equipe foram implementados e publicados.
- [x] A API do pedido foi criada e testada.
- [x] A tela de pedido grava e lê os pedidos pela API.

### Problemas conhecidos

Nenhum problema conhecido.

---

## 5. Retrospectiva da Sprint

### Manter

Fazer primeiro os ajustes menores e criar a API antes da tela.

### Melhorar

Não houve nenhum ponto explícito que exija melhoria.

### Agir

Publicar no vercel pela conta da Anna no início da Sprint 6 e conferir o fluxo na aplicação publicada.

---

## 6. Planejamento da próxima Sprint

### Meta da próxima Sprint

Disponibilizar o registro de pedidos e o fechamento de caixa na aplicação no vercel.

### Itens inicialmente selecionados

| User Story ou item | Responsável(is), se definido(s) | Resultado esperado |
|---|---|---|
| Publicar o backend pela conta da Anna | Anna Hermes | Pedidos registrados pela aplicação publicada |
| Senha de acesso ao dashboard | A definir | Dashboard aberto só com a senha |
| Cor do pedido conforme o prazo de entrega | A definir | Pedido muda de cor quando estiver perto do prazo de entrega e quando estiver atrasado |
| Testes de sistema e ajustes finais | Equipe | Sistema testado de ponta a ponta e ajustes aplicados para a entrega final |
| Montagem de Apresentação | Equipe | Montar a apresentação para a Mostra de Projetos de Desenvolvimento |

### Riscos ou impedimentos previstos

Nenhum risco identificado.
