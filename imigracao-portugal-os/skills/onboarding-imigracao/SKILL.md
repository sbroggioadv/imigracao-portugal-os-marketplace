---
name: onboarding-imigracao
description: "primeira interação guiada por botões; grava perfil, nacionalidade, localização, objetivo, títulos e datas críticas. Frentes 👤💼⚖️. Travas T1,T7. Portugal — Lei 23/2007 + reformas 2024-2026. Zero número operacional hardcoded; URL oficial + data. Use em: /start-imigracao-portugal, configurar, primeira vez."
---

> **🖱️ Escolhas = botões:** nas listas fechadas use **AskUserQuestion** (máx. 4 opções; se houver mais, divida).

# ONBOARDING IMIGRACAO

> **Camada C0** · Frentes: 👤 imigrante · 💼 comercial · ⚖️ advogado  
> Plugin: `imigracao-portugal-os` · Régua: `context/anexo-travas-portugal.md` (10 travas)

## Papel
primeira interação guiada por botões; grava perfil, nacionalidade, localização, objetivo, títulos e datas críticas

## Anexos
`context/anexo-travas-portugal.md`

## Travas aplicáveis
- **T1:** CPA 67 (atos pessoais/mandatário) × Lei 10/2024 (consulta e mandato forense reservados) × OA; OAB sozinha não confere título PT (Lei 6/2024 revogou reciprocidade especial).
- **T7:** Nacionalidade nova: 7 anos para lusófono em pedidos novos (LO 1/2026 desde 19/05/2026); pendentes conservam lei antiga; ARP/ERLD ≠ cidadania.

## Disclaimer (uma linha)
Não substitui profissional habilitado em Portugal (OA/solicitador) nem garante concessão de visto, AR ou nacionalidade. Código e páginas oficiais vencem a memória do modelo.


## Fluxo (botões AskUserQuestion)

1. **Frente:** 👤 Imigrante · 💼 Comercial · ⚖️ Advogado · Só estudar o plugin.
2. **Objetivo:** entrar/trabalhar · estudar · rendimento/remote · família · nacionalidade · já tenho processo · não sei.
3. **Onde está agora:** Brasil · Portugal com AR/visto · Portugal sem título / NAV · outro.
4. **Nacionalidade / CPLP:** brasileiro · outro lusófono · UE · outro.
5. **Datas:** tem protocolo/título/notificação com data? (texto livre se sim).

### ⛔ Se houver NAV ou irregularidade
Não minimizar. Abrir `nav-e-permanencia-irregular` e, se preciso, `afastamento-coercivo` **antes** de vender rota bonita.

### ⛔ Se o objetivo for “regularizar como turista / MI”
Aplicar **T3**: não existe porta nova de manifestação de interesse. Só legado com prova de data.

Grave o perfil localmente (persona do usuário) e devolva ao `imigracao-master`.


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
