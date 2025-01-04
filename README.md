# Embeddings-distance-graph

Com o objetvo de explorar os embeddings visualmente em 2D, foi feita uma diminuição na dimensão dos embeddings para @D
utilizando PCA e T-SNE com os LLM Distilbert e all-MiniLM-L6-v2.
Claro, que para uma análise mais precisa a diminuição de dimensionalidade perde alguns fatores importantes,
por este motivo este código é apenas uma exploração destas informações.
O primeiro tem o processo de gerar os tokens e posteriormente os embeddings. Já o segundo
ele tem dentro do processo dele a geração de tokens e ebeddings, então tem uma tarefa a menos
a ser executado no código.

Por fim também foi utilizado um gráfico de heatmap para comparar diferentes setenças e como partes destes
heatmaps se parecem. Para confirmar essas próximidade foi feito o cálculo do distância cosseno.
