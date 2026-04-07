# 05 — Matriz de Eventos

## Objetivo
Eliminar improviso de transição.

## Regra
Cada fase possui:
- evento de entrada
- ator responsável
- saída obrigatória
- atualização de estado
- próximo evento permitido

---

## Camada 1

### Fase 1 — Abertura
- evento de entrada: contexto inicial validado
- ator: sistema
- saída obrigatória: estado ativo + objetivo + bloco esperado + menu
- atualização: camada 1 aberta
- próximo evento permitido: emissão de contrato de turno

### Fase 2 — Contribuição
- evento de entrada: contrato de turno emitido
- ator: agente
- saída obrigatória: bloco de anotação + estrutura de encerramento
- atualização: contribuição recebida
- próximo evento permitido: consolidação

### Fase 3 — Consolidação
- evento de entrada: bloco recebido
- ator: sistema
- saída obrigatória: contexto ativo atualizado + pendência principal + menu
- atualização: valor incorporado / pendente / rejeitado
- próximo evento permitido: novo contrato ou passagem

### Fase 4 — Passagem
- evento de entrada: critérios de fechamento satisfeitos
- ator: sistema
- saída obrigatória: envelope da camada 1
- atualização: camada 2 liberada
- próximo evento permitido: abertura da camada 2

---

## Camada 2

### Fase 1 — Abertura
- evento de entrada: envelope da camada 1
- ator: sistema
- saída obrigatória: estado ativo + objetivo + bloco esperado + menu
- atualização: camada 2 aberta
- próximo evento permitido: emissão de contrato de turno

### Fase 2 — Contribuição
- evento de entrada: contrato de turno emitido
- ator: agente
- saída obrigatória: bloco de anotação + estrutura de encerramento
- atualização: contribuição recebida
- próximo evento permitido: consolidação

### Fase 3 — Consolidação
- evento de entrada: bloco recebido
- ator: sistema
- saída obrigatória: contexto ativo atualizado + pendência principal + menu
- atualização: valor incorporado / pendente / rejeitado
- próximo evento permitido: novo contrato ou passagem

### Fase 4 — Passagem
- evento de entrada: critérios de fechamento satisfeitos
- ator: sistema
- saída obrigatória: envelope da camada 2
- atualização: camada 3 liberada
- próximo evento permitido: abertura da camada 3

---

## Camada 3

### Fase 1 — Abertura
- evento de entrada: envelope da camada 2
- ator: sistema
- saída obrigatória: estado ativo + objetivo + bloco esperado + menu
- atualização: camada 3 aberta
- próximo evento permitido: emissão de contrato de turno

### Fase 2 — Contribuição
- evento de entrada: contrato de turno emitido
- ator: agente
- saída obrigatória: bloco de anotação + estrutura de encerramento
- atualização: contribuição recebida
- próximo evento permitido: consolidação

### Fase 3 — Consolidação
- evento de entrada: bloco recebido
- ator: sistema
- saída obrigatória: contexto ativo atualizado + pendência principal + menu
- atualização: definição operacional em fechamento
- próximo evento permitido: passagem

### Fase 4 — Passagem
- evento de entrada: critérios de fechamento satisfeitos
- ator: sistema
- saída obrigatória: pacote operacional
- atualização: modo X liberado
- próximo evento permitido: abertura do modo X
