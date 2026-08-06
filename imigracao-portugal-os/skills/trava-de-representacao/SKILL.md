---
name: trava-de-representacao
description: "GATE 2 — CPA × Lei 10/2024 × OA; quem pode aconselhar e mandatar em PT. Frentes 💼⚖️. Travas T1. Portugal — Lei 23/2007 + reformas 2024-2026. Zero número operacional hardcoded; URL oficial + data. Use em: representar, OAB, OA, mandatário, consultor, advogado em portugal."
---

> **🖱️ Escolhas = botões:** nas listas fechadas use **AskUserQuestion** (máx. 4 opções; se houver mais, divida).

# TRAVA DE REPRESENTACAO

> **Camada C1** · Frentes: 💼 comercial · ⚖️ advogado  
> Plugin: `imigracao-portugal-os` · Régua: `context/anexo-travas-portugal.md` (10 travas)

## Papel
GATE 2 — CPA × Lei 10/2024 × OA; quem pode aconselhar e mandatar em PT

## Anexos
`context/anexo-representacao-e-comercial.md`, `context/anexo-travas-portugal.md`

## Travas aplicáveis
- **T1:** CPA 67 (atos pessoais/mandatário) × Lei 10/2024 (consulta e mandato forense reservados) × OA; OAB sozinha não confere título PT (Lei 6/2024 revogou reciprocidade especial).

## Disclaimer (uma linha)
Não substitui profissional habilitado em Portugal (OA/solicitador) nem garante concessão de visto, AR ou nacionalidade. Código e páginas oficiais vencem a memória do modelo.


## A interseção portuguesa (não é a lista fechada dos EUA)

| Quem | Pode | Não pode |
|---|---|---|
| **Cliente** | Atos pessoais (CPA 67.º); biometria/entrevista quando exigidas | — |
| **Mandatário administrativo** | Representar/assistir no procedimento nos limites do CPA e do fluxo do órgão | Transformar-se em consultor jurídico PT disfarçado |
| **Advogado/solicitador OA** | Consulta jurídica, mandato forense administrativo/judicial (Lei 10/2024) | Atuar sem inscrição/seguro quando exigido |
| **Só OAB (sem OA)** | Direito BR, documentos BR, educação geral, coordenação | “Advogado em Portugal”, parecer de Direito PT, mandato forense PT, G-28-style inventado |
| **“Consultor de imigração”** | Logística/educação geral **sem** conselho jurídico individualizado | Ato reservado; credencial “AIMA” inventada |

### Frases bloqueadas
- “Com OAB você já é advogado em Portugal.” (revogado desde 01/04/2024)
- “Sou representante credenciado AIMA.” (sem fonte)
- “Eu te represento na AIMA e escolho a tese” (só OAB / consultor sem habilitação)

### Modelo legítimo
Cliente (atos pessoais) + camada BR (OAB/docs) + profissional PT habilitado (consulta/mandato) com identidades e honorários separados — ver `arquitetura-servico-br-pt`.


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
