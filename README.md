# Santiago

<img src="./img/SantiagoQuant.jpg">

O algoritmo Santiago adota uma estratégia cuidadosamente planejada para a compra e venda de diversos ativos no mercado. Começando pelo ponto de partida, ele coleta uma ampla gama de dados de mercado, abrangendo índices, commodities, taxas de câmbio e ações de todo o mundo. Essa diversidade de informações é a base fundamental para nossa análise.

A primeira etapa consiste em submeter esses dados a um rigoroso processo de pré-processamento. Esse procedimento tem como objetivo identificar informações altamente relevantes para cada ativo específico. Após a conclusão da limpeza e depuração dos dados, avançamos para a segunda etapa, onde aplicamos uma Variational Autoencoder (VAE). Essa rede neural generativa desempenha um papel crucial, permitindo-nos gerar dados sintéticos e criar representações de alto nível dos dados para o nosso modelo.

Além disso, utilizamos técnicas de Análise de Componentes Principais (PCA) para extrair informações adicionais e características significativas dos dados. Essas novas variáveis são cuidadosamente incorporadas ao conjunto original de dados, enriquecendo nossa base de conhecimento.

A partir deste ponto, entramos em uma fase crucial, onde selecionamos as variáveis que apresentam forte correlação com o preço das ações que estamos buscando prever. Após a normalização dos dados, nossa arquitetura incorpora a tecnologia LSTM (Long Short Term Memory), um modelo poderoso que nos permite realizar análises de regressão e projetar tendências futuras. É importante destacar que esta etapa é apenas uma parte integrante do algoritmo geral.

Esse procedimento é repetido para várias ações no mercado, proporcionando-nos a capacidade de fazer previsões diárias sobre o desempenho das ações. Em seguida, aplicamos uma estratégia de alocação de portfólio para ajustar as ponderações de cada ativo. Nosso principal objetivo ao fazer isso é maximizar o Índice de Sharpe, seguindo os princípios da Teoria Moderna do Portfólio de Markowitz.

Em resumo, nosso algoritmo não apenas realiza previsões de desempenho de ações, mas também incorpora uma estratégia de alocação de portfólio que visa otimizar o retorno ajustado ao risco. A combinação de pré-processamento de dados, engenharia de características, modelagem com LSTM e estratégia de portfólio torna nossa abordagem completa e robusta na busca por melhores resultados nos mercados financeiros.
