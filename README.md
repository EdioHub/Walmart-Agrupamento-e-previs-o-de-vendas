# Análise de Vendas, Segmentação de Clientes e Previsão de Vendas do Walmart nos Estados Unidos
Este projeto tem como objetivo realizar uma análise abrangente das vendas do Walmart nos Estados Unidos, durante o período de 2011 a 2014. Além disso, serão aplicadas técnicas de segmentação de clientes e previsão de vendas utilizando um modelo de séries temporais com o Prophet.

##Pré-processamento do Dataset

Inicialmente, será realizado o pré-processamento do dataset, que envolverá a limpeza e transformação dos dados para garantir sua qualidade e adequação para as análises subsequentes. Serão tratados valores ausentes, ajustadas as colunas de data e formatos de dados, e realizada uma análise exploratória para obter insights preliminares.

##Segmentação de Clientes com K-means

Utilizando a técnica de agrupamento K-means, faremos uma segmentação dos clientes do Walmart com base em critérios como faturamento, lucros e quantidade de produtos vendidos  Essa segmentação permitirá uma melhor compreensão do comportamento e características dos diferentes grupos de clientes.

##Otimização de Quantidade de Classes com Elbow

Utilizaremos o método Elbow para determinar a quantidade ideal de classes para a segmentação dos clientes. Através dessa técnica, identificaremos o ponto de inflexão no gráfico de variância explicada em relação ao número de classes, a fim de encontrar o número ótimo de grupos para a análise.

##Análise das 4 Classes Agrupadas

Após a segmentação, realizaremos uma análise aprofundada das 4 (redução feita para otimização de processamento) classes agrupadas de clientes, explorando características distintas, comportamentos de compra e possíveis estratégias de marketing direcionadas a cada grupo. Essa análise contribuirá para o desenvolvimento de ações mais personalizadas e eficazes.

##Modelo de Séries Temporais com Prophet para Previsão de Vendas

Por fim, aplicaremos o modelo Prophet, uma técnica de séries temporais, para realizar a previsão de vendas futuras do Walmart. Utilizaremos os dados históricos disponíveis para criar um modelo robusto e preciso, capaz de gerar previsões confiáveis para auxiliar no planejamento estratégico e na tomada de decisões.
