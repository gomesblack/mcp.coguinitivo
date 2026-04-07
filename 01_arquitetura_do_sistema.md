# 01 — Arquitetura do Sistema

## Definição
O sistema é um **orquestrador conversacional para uso estruturado do NotebookLM**.

## Missão
Receber uma entrada válida, abrir uma reunião em camadas, converter contribuições em blocos documentais, consolidar contexto e gerar um pacote operacional para o modo X.

## O que o sistema é
- controlador de estado
- controlador de fase
- editor de contexto ativo
- gestor de passagem entre camadas
- preparador de operação para o NotebookLM

## O que o sistema não é
- não é o NotebookLM
- não é um agente especialista único
- não é um debate livre
- não é um gerador de respostas contínuas sem turnos
- não é um detector garantido da interface do usuário

## Blocos da arquitetura

### Bloco A — Orquestrador
Função:
- abrir fase
- definir contrato de turno
- registrar entregas
- atualizar contexto ativo
- exibir menu
- fechar fase
- gerar envelope
- liberar modo X

### Bloco B — Agentes
Função:
- produzir blocos de anotação
- usar cognição própria
- atuar dentro do contrato de turno
- encerrar com estrutura obrigatória de saída

### Bloco C — Usuário
Função:
- fornecer entrada inicial
- operar pelos menus
- chamar agente quando isso estiver previsto
- escolher o rumo macro entre as opções válidas

### Bloco D — NotebookLM
Função:
- receber a aplicação preparada
- servir como ambiente de operação no modo X

## Modos do sistema

### Modo reunião
Características:
- fluxo rígido
- turnos intercalados
- alto controle de fase
- contexto ativo enxuto
- consolidação por blocos e envelopes

### Modo X
Características:
- execução orientada
- agente operador com liberdade especializada
- fidelidade ao pacote operacional
- sem reabertura da reunião

## Regra estrutural
A reunião não se sustenta por memória vaga.
Ela se sustenta por:
- estado
- contrato de turno
- bloco de anotação
- contexto ativo
- envelope
- critérios de fechamento
