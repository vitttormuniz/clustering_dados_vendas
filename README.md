# Projeto de Clustering em Dados de Vendas
Este projeto aplica diferentes algoritmos de clustering a um conjunto de dados de vendas para agrupar clientes com base em suas compras. Utilizamos algoritmos de K-Means, DBSCAN, Agglomerative Clustering (Hierarchical) e Mean Shift, além de calcular métricas de avaliação como Silhouette Score, Davies-Bouldin Index e Calinski-Harabasz Index.

# Visão Geral do Projeto
Este projeto realiza clustering em dados de vendas, onde clientes são agrupados com base em seus comportamentos de compra. O objetivo é identificar padrões, comportamentos e perfis de clientes a partir das informações transacionais, como o valor total de vendas e a quantidade de transações.

# Algoritmos de Clustering Utilizados:
- K-Means
- DBSCAN
- Agglomerative Clustering (Hierarchical)
- Mean Shift

# Métricas de Avaliação:
- Silhouette Score
- Davies-Bouldin Index
- Calinski-Harabasz Index
Essas métricas são usadas para avaliar a qualidade dos clusters gerados por cada algoritmo.

# Tecnologias Utilizadas
- Python: Linguagem de programação principal.
- Pandas: Manipulação e análise de dados.
- NumPy: Computação numérica.
- Scikit-learn: Implementação dos algoritmos de clustering e métricas de avaliação.
- Seaborn e Matplotlib: Visualização dos dados e clusters.

# Dataset
O dataset data.csv contém colunas como:

- InvoiceNo: Número da fatura.
- StockCode: Código do item.
- Description: Descrição do item.
- Quantity: Quantidade comprada.
- InvoiceDate: Data da transação.
- UnitPrice: Preço unitário do item.
- CustomerID: Identificação do cliente.
- Country: País de origem da compra.

# Resultados
Os resultados de cada algoritmo são apresentados com suas respectivas métricas de avaliação. Utilizando essas métricas, podemos comparar a qualidade dos clusters gerados por cada abordagem e escolher a melhor para os dados em questão.

# Visualização dos Clusters:
Clusters podem ser visualizados utilizando bibliotecas como Seaborn ou Matplotlib para auxiliar na análise do comportamento dos clientes.
