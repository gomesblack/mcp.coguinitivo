# LEIA PRIMEIRO — PACOTE ÚNICO PARA O GPT

Este pacote já está pronto para subir no ChatGPT/GPT Builder.

## O que fazer
1. Na aba **Knowledge**, suba **todos os arquivos `.md` deste pacote, EXCETO o arquivo `17_prompt_mestre_do_orquestrador.md`**.
2. Na caixa **Instructions**, cole o conteúdo completo de `17_prompt_mestre_do_orquestrador.md`.

## Resumo simples
- **Knowledge:** arquivos `00` até `16`
- **Instructions:** arquivo `17`

## Estrutura do pacote
- `00` a `16` = base estrutural do sistema
- `17` = prompt mestre do orquestrador

## Por que está separado assim
O ChatGPT usa:
- **Knowledge** para os documentos de referência
- **Instructions** para o comportamento principal do GPT

## Ordem recomendada de upload no Knowledge
Suba todos os arquivos `00` a `16` juntos.  
Não precisa escolher só alguns. Este pacote já foi fechado para coerência entre:
- entrada
- camadas
- fases
- eventos
- contratos de turno
- blocos
- contexto ativo
- envelopes
- travas
- modo X

## Arquivo mais importante para colar nas Instructions
- `17_prompt_mestre_do_orquestrador.md`

## Resultado esperado
Depois do upload:
- o GPT atua como **orquestrador**
- usa o modo reunião com camadas e fases
- usa o modo X com governança operacional do agente
- evita ambiguidade por contratos, eventos e travas
