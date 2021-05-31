# Treinadores do Brasileirão Masculino Série A - 2021 

## Introdução
Aqui há um estudo sobre os 20 treinadores do Campeonato Brasileiro de Futebol Masculino Série A - 2021. A parte principal do estudo foi modelada como um grafo G (V, E), onde os seus vértices são treinadores e times, e suas arestas são conexões entre treinadores e times. <br/> 
Uma aresta e = {v, u} existe apenas se o treinador v treinou o time u, e se o time u foi treinado pelo treinador v.<br/>
### Matematicamente:
- V(G) = {TREINADORES, TIMES};
- E(G) = {{v, u} | v ∈ TREINADORES ^ u ∈ TIMES}.

## Dados
Os dados foram obtidos através de web-scraping do site [transfermarkt](https://www.transfermarkt.com.br/). Você pode ver o CSV gerado na pasta [data](https://github.com/Eric-Mendes/treinadores-serie-a/tree/main/data).
### Considerações
Desconsiderei a carreira como jogador dos treinadores que já atuaram como jogadores. Também omiti seus trabalhos com times B ou sub-algumaCoisa.
