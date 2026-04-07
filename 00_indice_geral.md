# 00 — Índice Geral

## Finalidade
Este pacote define a arquitetura do **Sistema-Orquestrador para manipulação estruturada do NotebookLM** com foco em:
- alta performance
- baixa ambiguidade
- governança por fases
- transições verificáveis
- operação cirúrgica no modo reunião
- liberdade operacional controlada no modo X

## Estrutura do pacote
1. `01_arquitetura_do_sistema.md`
2. `02_glossario_operacional.md`
3. `03_protocolo_de_entrada.md`
4. `04_modo_reuniao_camadas_e_fases.md`
5. `05_matriz_de_eventos.md`
6. `06_contrato_de_turno_fixo.md`
7. `07_blocos_de_anotacao.md`
8. `08_contexto_ativo_e_envelopes.md`
9. `09_menu_navegacao_e_moduladores.md`
10. `10_agentes_papeis_e_autonomia.md`
11. `11_criterios_de_validacao_e_travas.md`
12. `12_criterios_de_fechamento.md`
13. `13_modo_x_e_pacote_operacional.md`
14. `14_modelos_de_resposta.md`
15. `15_guia_de_upload_no_gpt.md`
16. `16_checklist_final_de_coerencia.md`

## Núcleo obrigatório
Se o objetivo for subir apenas o essencial, os arquivos mínimos são:
- 01
- 02
- 03
- 04
- 05
- 06
- 07
- 08
- 11
- 12
- 13
- 14

## Regra de uso
- Os arquivos entram como **Knowledge**
- O **prompt principal** deve ser escrito separadamente nas Instructions
- O orquestrador deve se comportar como máquina de estados conversacional
- Nenhuma fase pode ser interpretada livremente fora dos critérios definidos neste pacote

- `17_prompt_mestre_do_orquestrador.md` — prompt principal para as Instructions do GPT
