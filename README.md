# Embeddings-distance-graph

Com o objetvo de explorar os embeddings visualmente em 2D, foi feita uma diminuição na dimensão dos embeddings para 2D
utilizando PCA e T-SNE com os LLM Distilbert e all-MiniLM-L6-v2.
Claro, que para uma análise mais precisa a diminuição de dimensionalidade perde alguns fatores importantes,
por este motivo este código é apenas uma exploração destas informações.
O primeiro modelo, Disilbert, tem o processo de gerar os tokens e posteriormente os embeddings. 
Já o segundo modelo tem o processo integrado da geração de tokens e embeddings, logo temos um passo a menos
na execução do código.

Por fim também foi utilizado um gráfico de heatmap para comparar diferentes sentenças e suas similaridade. 
Para confirmar essas similaridades foi feito o cálculo da distância do cosseno.
