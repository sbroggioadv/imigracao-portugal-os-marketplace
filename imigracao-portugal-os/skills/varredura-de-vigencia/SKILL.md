---
name: varredura-de-vigencia
description: "GATE 1 — lei consolidada + execução do dia; anti-defasagem T3–T8. Frentes 👤💼⚖️. Travas T3,T4,T5,T6,T7,T8. Portugal — Lei 23/2007 + reformas 2024-2026. Zero número operacional hardcoded; URL oficial + data. Use em: vigência, atualizou, lei 61/2025, lei 1/2026, taxa, portal."
---

> **🖱️ Escolhas = botões:** nas listas fechadas use **AskUserQuestion** (máx. 4 opções; se houver mais, divida).

# VARREDURA DE VIGENCIA

> **Camada C1** · Frentes: 👤 imigrante · 💼 comercial · ⚖️ advogado  
> Plugin: `imigracao-portugal-os` · Régua: `context/anexo-travas-portugal.md` (10 travas)

## Papel
GATE 1 — lei consolidada + execução do dia; anti-defasagem T3–T8

## Anexos
`context/anexo-travas-portugal.md`, `context/anexo-fundacao-normativa.md`

## Travas aplicáveis
- **T3:** Sem nova manifestação de interesse (DL 37-A/2024; transição fechada 31/12/2025).
- **T4:** Procura de trabalho agora é **qualificada** (art. 57.º-A); operação/portaria pode estar NAO-PROVADA — reler no dia.
- **T5:** CPLP exige visto prévio + biometria + cartão uniforme (não certificado online mágico).
- **T6:** Reagrupamento pós-Lei 61/2025: espera/exceções + prazo especial de decisão (não narrativa antiga de 3 meses).
- **T7:** Nacionalidade nova: 7 anos para lusófono em pedidos novos (LO 1/2026 desde 19/05/2026); pendentes conservam lei antiga; ARP/ERLD ≠ cidadania.
- **T8:** Silêncio em AR **inicial** não aprova; deferimento tácito é da **renovação** (art. 82.º).

## Disclaimer (uma linha)
Não substitui profissional habilitado em Portugal (OA/solicitador) nem garante concessão de visto, AR ou nacionalidade. Código e páginas oficiais vencem a memória do modelo.


## Como rodar o GATE 1

Para **cada** afirmação operacional (taxa, formulário, portal, requisito mutável, prazo de processamento):

1. Abrir a **versão consolidada** no diariodarepublica.pt do diploma.
2. Abrir a **página operacional** do órgão (aima.gov.pt, vistos.mne.gov.pt, irn.justica.gov.pt, etc.).
3. Registrar **URL + data/hora** da consulta.
4. Classificar: `CONFIRMADO` · `TRANSICAO` · `CONFLITO` · `NAO-PROVADO`.
5. `TRANSICAO` e `CONFLITO` **nunca** viram resposta categórica.

### Gatilhos obrigatórios deste gate
Lei 61/2025 · LO 1/2026 · procura qualificada · CPLP · reagrupamento · taxas AIMA · portais · proteção temporária · inscrição OA.

### Fontes de topo
https://diariodarepublica.pt · https://aima.gov.pt · https://vistos.mne.gov.pt · https://irn.justica.gov.pt · https://eur-lex.europa.eu


## URLs de topo (sempre preferir estas)
- Diário da República: https://diariodarepublica.pt  
- AIMA: https://aima.gov.pt  
- Vistos MNE: https://vistos.mne.gov.pt  
- IRN/Justiça: https://irn.justica.gov.pt · https://justica.gov.pt  
- OA: https://portal.oa.pt  
- EUR-Lex: https://eur-lex.europa.eu  

## Saída esperada
1. Frente + fase + localização + **data do ato** usada.  
2. Regime jurídico aplicável (com dispositivo + URL + data de leitura).  
3. O que fazer agora / o que não fazer (⛔).  
4. Lacunas `NAO-PROVADO` declaradas.  
5. Próxima skill ou referral (OA / consulado / AIMA / IRN).

## Guard
- Zero taxa/cota/prazo de processamento hardcoded.  
- Zero promessa de resultado ou prazo de aprovação.  
- Zero copiar trava dos EUA (292.1) como se fosse Portugal.  
- Byte cap: manter este arquivo ≤ 11.000 B.
