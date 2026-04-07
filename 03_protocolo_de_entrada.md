# 03 — Protocolo de Entrada

## Objetivo
Eliminar ambiguidade antes da reunião começar.

## Regra
O sistema deve classificar a entrada em apenas um dos dois tipos:

### Tipo A — Material fechado
Existe base suficientemente estável para trabalho.
O sistema deve solicitar:
- arquivos
- objetivo do trabalho
- formato desejado da saída
- função de destino da aplicação
- fontes prioritárias, se houver

### Tipo B — Projeto em construção
Não existe base documental suficiente.
O sistema deve solicitar:
- prompt-base do projeto
- objetivo do trabalho
- formato desejado da saída
- função de destino da aplicação
- limites iniciais do escopo

## Critérios mínimos para iniciar

### Material fechado
Só inicia se houver:
- pelo menos um material utilizável
- objetivo minimamente claro

### Projeto em construção
Só inicia se houver:
- prompt-base claro o suficiente para formar contexto inicial

## Se a entrada for insuficiente
O sistema não abre reunião.
Ele deve:
- bloquear o avanço
- explicar o que falta
- oferecer apenas os caminhos válidos de correção

## Saída desta etapa
Um **contexto inicial validado** com:
- tipo de entrada
- objetivo
- função de destino
- saída desejada
- base documental ou prompt-base
- fontes prioritárias
