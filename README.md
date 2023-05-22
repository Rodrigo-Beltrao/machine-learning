# machine-learning
Este projeto envolveu a análise e clusterização de clientes de um supermercado. O objetivo era entender melhor o comportamento dos clientes e identificar grupos distintos com características semelhantes. O processo do projeto incluiu as seguintes etapas:

1)Kaggle: A obtenção dos dados foi feita por meio da plataforma Kaggle, que oferece conjuntos de dados públicos para análise.

2)Coleta de Dados: Os dados relevantes para o projeto foram coletados a partir do conjunto de dados disponibilizado no Kaggle. Esses dados continham informações demográficas, comportamentais e de compra dos clientes.

3)Análise Exploratória - Parte I: Nesta etapa, foi realizada uma análise exploratória inicial dos dados. Isso incluiu a verificação da qualidade dos dados, identificação de valores ausentes ou inconsistentes, e uma visão geral das principais variáveis do conjunto de dados.

4)Análise Exploratória - Parte II: A segunda parte da análise exploratória envolveu uma investigação mais aprofundada das características individuais dos clientes. Foram examinadas variáveis como renda, nível educacional, idade, estado civil e presença de filhos. Isso ajudou a identificar padrões e tendências relevantes para o projeto.

5)Análise Exploratória - Parte III: Nesta etapa, foi realizada uma análise mais específica das variáveis relacionadas aos hábitos de compra dos clientes. Foram investigados os gastos em diferentes categorias de produtos, o tempo desde a última compra e a taxa de aceitação de campanhas de marketing.

6)Normalização: Antes de prosseguir com a clusterização, as variáveis relevantes foram normalizadas para garantir que todas estivessem na mesma escala. Isso é importante para evitar o viés causado por unidades de medida diferentes.

7)Método de Elbow: O método de Elbow foi utilizado para determinar o número ideal de clusters. Foram testados diferentes valores e avaliadas as variações intra e inter-cluster para identificar o ponto em que a adição de mais clusters não fornecia uma melhoria significativa na variabilidade dos dados.

8)Alocação de Pesos: As variáveis relevantes foram ponderadas com base em sua importância relativa para o projeto. Isso ajudou a destacar as características mais relevantes na formação dos clusters.

9)Treinamento: O algoritmo de clusterização foi treinado usando as variáveis ponderadas e o número ideal de clusters determinado anteriormente. O algoritmo utilizado pode ter sido o K-means, DBSCAN, Hierarchical Clustering ou qualquer outro adequado para o problema.

10)Alocação e Análise de Clusters: Os clientes foram alocados nos clusters correspondentes com base em suas características individuais. Em seguida, cada cluster foi analisado individualmente, considerando as médias das variáveis relevantes. Foram identificadas as características distintivas de cada cluster, incluindo renda, nível educacional, idade, estado civil, presença de filhos, padrões de gastos e taxa de aceitação de campanhas de marketing.

Em resumo, a análise de cluster revelou diferentes perfis de clientes no supermercado:

    Cluster 1: Clientes com renda alta, nível educacional médio, idade madura, tempo médio desde a última compra de 51 dias e alta taxa de aceitação de campanhas de marketing. Eles têm preferência por produtos de alta qualidade e têm um poder de compra considerável.

    Cluster 3: Clientes com renda e nível educacional relativamente baixos, tempo médio maior desde a última compra e baixa taxa de aceitação de campanhas de marketing. Eles têm prioridades financeiras voltadas para a família e são menos responsivos às estratégias tradicionais de marketing.

    Cluster 2: Clientes com renda alta, nível educacional médio, tempo médio curto desde a última compra, casados ou em relacionamento estável e com filhos. Eles apresentam preferência por alimentos saudáveis e têm um poder de compra considerável. A taxa de aceitação de campanhas de marketing é moderada.

    Cluster 0: Clientes com renda relativamente baixa, nível educacional mais baixo, idade em torno de 50 anos, solteiros e com filhos. Eles têm um consumo moderado de produtos e um poder de compra mais limitado. A taxa de aceitação de campanhas de marketing é baixa, indicando uma maior seletividade.

Essas informações fornecem uma visão abrangente dos diferentes grupos de clientes, permitindo ao supermercado adaptar suas estratégias de marketing, oferta de produtos e serviços de acordo com as necessidades e preferências de cada segmento. Isso pode levar a um aumento na satisfação do cliente, fidelização e crescimento dos negócios.
