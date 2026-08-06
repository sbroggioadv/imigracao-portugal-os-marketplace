---
name: diagnostico-de-elegibilidade-pt
description: "compara requisitos legais e bloqueios sem prometer concessão. Frentes 👤⚖️. Travas T2-T7. Portugal — Lei 23/2007 + reformas 2024-2026. Zero número operacional hardcoded; URL oficial + data. Use em: elegível, qual visto, posso ir."
---

> **🖱️ Escolhas = botões:** nas listas fechadas use **AskUserQuestion** (máx. 4 opções; se houver mais, divida).

# DIAGNOSTICO DE ELEGIBILIDADE PT

> **Camada C2** · Frentes: 👤 imigrante · ⚖️ advogado  
> Plugin: `imigracao-portugal-os` · Régua: `context/anexo-travas-portugal.md` (10 travas)

## Papel
compara requisitos legais e bloqueios sem prometer concessão

## Anexos
`context/anexo-vistos-e-residencia.md`

## Travas aplicáveis
- **T2:** Visto de residência ≠ autorização/título de residência (Lei 23/2007 art. 58.º — vinheta habilita estada limitada; AR é outro ato).
- **T3:** Sem nova manifestação de interesse (DL 37-A/2024; transição fechada 31/12/2025).
- **T4:** Procura de trabalho agora é **qualificada** (art. 57.º-A); operação/portaria pode estar NAO-PROVADA — reler no dia.
- **T5:** CPLP exige visto prévio + biometria + cartão uniforme (não certificado online mágico).
- **T6:** Reagrupamento pós-Lei 61/2025: espera/exceções + prazo especial de decisão (não narrativa antiga de 3 meses).
- **T7:** Nacionalidade nova: 7 anos para lusófono em pedidos novos (LO 1/2026 desde 19/05/2026); pendentes conservam lei antiga; ARP/ERLD ≠ cidadania.

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
