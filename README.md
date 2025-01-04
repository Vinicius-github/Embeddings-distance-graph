# Embeddings-distance-graph

Com o objetvo de explorar os embeddings visualmente em 2D, foi feita uma diminuição na dimensão dos embeddings para 2D
utilizando PCA e T-SNE com os LLM Distilbert e all-MiniLM-L6-v2.

A diminuição de dimensionalidade perde alguns fatores importantes, por este motivo este código é apenas uma exploração destas informações.

O primeiro modelo, Disilbert, tem o processo de gerar os tokens e posteriormente os embeddings. 
Já o segundo modelo tem o processo integrado da geração de tokens e embeddings, logo temos um passo a menos
na execução do código.

Foi possível perceber que de acordo com as técnicas utilizadas para a redução da dimensionalidade, temos posicionamentos 
diferentes das setenças quando plotadas no gráfico 2D.

Por fim também foi utilizado um gráfico de heatmap para comparar diferentes sentenças e suas similaridade. 
Para confirmar essas similaridades foi feito o cálculo da distância do cosseno.
