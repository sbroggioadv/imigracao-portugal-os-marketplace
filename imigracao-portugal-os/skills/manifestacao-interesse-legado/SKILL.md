---
name: manifestacao-interesse-legado
description: "só processo/transição tempestiva com prova de data; sem porta nova. Frentes 👤💼⚖️. Travas T3. Portugal — Lei 23/2007 + reformas 2024-2026. Zero número operacional hardcoded; URL oficial + data. Use em: manifestação de interesse, MI, regularizar como turista."
---

> **🖱️ Escolhas = botões:** nas listas fechadas use **AskUserQuestion** (máx. 4 opções; se houver mais, divida).

# MANIFESTACAO INTERESSE LEGADO

> **Camada C4** · Frentes: 👤 imigrante · 💼 comercial · ⚖️ advogado  
> Plugin: `imigracao-portugal-os` · Régua: `context/anexo-travas-portugal.md` (10 travas)

## Papel
só processo/transição tempestiva com prova de data; sem porta nova

## Anexos
`context/anexo-travas-portugal.md`

## Travas aplicáveis
- **T3:** Sem nova manifestação de interesse (DL 37-A/2024; transição fechada 31/12/2025).

## Disclaimer (uma linha)
Não substitui profissional habilitado em Portugal (OA/solicitador) nem garante concessão de visto, AR ou nacionalidade. Código e páginas oficiais vencem a memória do modelo.


## Como operar esta skill

1. Confirmar **frente** e se os gates já rodaram nesta sessão; se não, chamar `varredura-de-vigencia` e/ou `trava-de-representacao`.
2. Pedir os **fatos mínimos**: nacionalidade, onde está, objetivo, datas de protocolo/título/notificação, documentos já obtidos.
3. Mapear **finalidade → dispositivo (Lei 23/2007 ou especial) → visto e/ou AR → canal (consulado/AIMA/IRN)** — nunca só pelo rótulo D1/D7/CPLP.
4. Montar entrega na profundidade da frente:
   - 👤 checklist e decisões honestas, sem minuta de mandato PT
   - 💼 escopo vendável, contrato e o que **não** vender
   - ⚖️ matriz norma→requisito→prova→remédio, com referral OA se faltar habilitação
5. Toda afirmação operacional: **URL oficial + data**. Sem fonte atual → `NAO-PROVADO`.
6. Antes de fechar entrega normativa: `validador-imigratorio` (e `suprema-corte-imigratoria` se ⚖️).


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
