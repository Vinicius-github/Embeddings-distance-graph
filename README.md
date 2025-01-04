# Embeddings distance graph

Com o objetvo de explorar os embeddings visualmente, foi proposto um código com a diminuição na dimensão dos embeddings para 2D
utilizando PCA e T-SNE.

A diminuição de dimensionalidade perde alguns fatores importantes, por este motivo este código é apenas uma exploração destas informações.

No primeiro momento foi utilizado o modelo Disilbert para gerar os embeddings. Ele tem o processo de gerar os tokens e posteriormente os embeddings. 
Já o segundo num segundo momento, foi utilizado o modelo all-MiniLM-L6-v2 onde o processo é integrado para a geração de tokens e embeddings, logo, temos um passo a menos
na execução do código.

Foi possível perceber que de acordo com as técnicas utilizadas para a redução da dimensionalidade, temos posicionamentos 
diferentes das setenças quando plotadas no gráfico 2D.

Por fim também foi utilizado um gráfico de heatmap para comparar diferentes sentenças e suas similaridade. 
Para confirmar essas similaridades foi feito o cálculo da distância do cosseno.
