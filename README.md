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


A análise de cluster revelou diferentes perfis de clientes no supermercado:

    Cluster 1: É composto por indivíduos com uma renda relativamente alta e um nível educacional médio. A média de idade dos               indivíduos é em torno de 54 anos, indicando que são pessoas maduras. Eles apresentam um tempo médio desde a última compra         de cerca de 51 dias, sugerindo um envolvimento ativo em atividades de compra.
    
        A maioria das pessoas neste cluster está casada ou em um relacionamento estável. É interessante notar que a maioria não           possui filhos, o que pode ter um impacto nas suas decisões de compra, pois podem ter mais liberdade para investir em si           mesmos.

        Em relação aos gastos, observa-se um alto consumo de vinhos, carne, peixe e produtos de ouro. Isso sugere que esses               indivíduos apreciam produtos de alta qualidade e estão dispostos a investir em itens que consideram luxuosos. O total             gasto em compras é relativamente alto, indicando que eles têm um poder de compra considerável.
    
        A taxa de aceitação de campanhas de marketing é alta, o que indica que estratégias de marketing direcionadas e                     personalizadas têm um bom impacto nesse grupo. Eles estão mais propensos a responder positivamente a ofertas e campanhas           que correspondam às suas preferências e estilo de vida.
        
 
     Cluster 3: Comparando com os outros clusters, o Cluster 3 é caracterizado por indivíduos com renda e nível educacional                relativamente baixos. Eles apresentam um tempo médio maior desde a última compra, o que pode indicar um menor engajamento          em atividades de compras online ou menos acesso a meios de compra. Além disso, a taxa de aceitação de campanhas de                marketing é baixa, o que sugere que esses indivíduos podem ser menos responsivos às estratégias tradicionais de                    marketing.

         Dado que eles têm filhos, é possível que suas prioridades financeiras estejam mais voltadas para a família, limitando              assim seus gastos em outras áreas. No entanto, ainda há um consumo moderado de produtos como vinhos, carnes e produtos            doces, o que indica algum interesse nessas categorias de produtos.
       
              
     Cluster 2: É caracterizado por indivíduos com uma renda relativamente alta e um nível educacional médio. Eles apresentam um            tempo médio razoavelmente curto desde a última compra, o que sugere um engajamento regular em atividades de compra.
        
         É interessante notar que a maioria dos indivíduos neste cluster está casada ou em um relacionamento estável, o que pode            influenciar suas preferências de consumo. Além disso, eles têm filhos, o que pode ser um fator que influencia suas                decisões de compra.
         
         Os gastos neste cluster indicam um consumo considerável de produtos como vinhos, frutas, carne e peixe. Isso sugere que            esses indivíduos possuem uma preferência por alimentos saudáveis e de qualidade. O total gasto em compras é relativamente          alto, indicando que eles estão dispostos a investir em produtos de sua preferência.
        
        A taxa de aceitação de campanhas de marketing é moderada, o que sugere que estratégias de marketing segmentadas e                 personalizadas podem ter algum impacto nesse grupo.


    Cluster 0: É composto por indivíduos com uma renda relativamente baixa e um nível educacional mais baixo. A média de idade dos         indivíduos é em torno de 50 anos, indicando que são pessoas em uma faixa etária mais jovem ou de meia-idade.
   
        A maioria das pessoas neste cluster é solteira, o que pode indicar um perfil mais independente e menos preocupado com             responsabilidades familiares. No entanto, a maioria possui filhos, o que pode influenciar suas decisões de compra.

        Em relação aos gastos, observa-se um consumo moderado de vinhos, frutas, carne e peixe. Isso sugere que esses indivíduos          tendem a adquirir produtos de forma equilibrada e não exagerada. O total gasto em compras é relativamente baixo, indicando        que eles têm um poder de compra mais limitado.
    
        A taxa de aceitação de campanhas de marketing é baixa, o que indica que estratégias de marketing tradicionais podem não           ser tão eficazes com esse grupo. Eles podem ser mais seletivos e céticos em relação a ofertas e campanhas publicitárias.  
    
    
Essas informações fornecem uma visão abrangente dos diferentes grupos de clientes, permitindo ao supermercado adaptar suas estratégias de marketing, oferta de produtos e serviços de acordo com as necessidades e preferências de cada segmento. Isso pode levar a um aumento na satisfação do cliente, fidelização e crescimento dos negócios.
