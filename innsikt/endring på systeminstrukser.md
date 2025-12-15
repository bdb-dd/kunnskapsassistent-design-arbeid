## Bakgrunnen for arbeidet

…

## Konklusjoner

- GPT4o er mer stabil
    - Gjør det den får beskjed om
    - Litt dårligere på formatering av tabeller enn gpt5
- GPT 5 er for kreativ
    - Kan hende den er bedre på agentisk RAG, men for øyeblikket foreslår den bare mye greier som vi veit at den ikke får til (som å lage en visuell framstilling av infoen, eller analysere alle statlige virksomheter selv om vi har sagt at det ikke går)
    - Bedre på formatering av tabeller i markdown

## Veien videre

1. Teste den siste instruksen på ulike spørsmål i sandkassemiljøet, for å se om den er bedre enn systeminstruksen vi har i prod
    1. Kan teste den på spørsmål vi allerede har i prod
2. Om vi konkluderer med at det blir en bedre sparringspartner så pusher vi det til prod