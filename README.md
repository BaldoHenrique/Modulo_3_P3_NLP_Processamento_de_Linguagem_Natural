# Modulo_3_P3_NLP_Processamento_de_Linguagem_Natural
Curso Ciência de dados da Blue Edtech - Análise de sentimento sobre o mercado financeiros


# Projeto 3 - Análise de sentimento sobre o mercado financeiro

## Entrega
  - O projeto deve ser entregue até a terça-feira da 4ª semana de aula, envie o link do GitHub ou HTML na atividade no Moodle.
  - O prazo máximo é quarta-feira da 4ª semana de aula, valendo 20% a menos da nota.

## Dados do Certificado
  - Linguagem: Python
  - Tecnologias: Pandas, Numpy, Spacy, Matplotlib e Sklearn
  - Carga horária: 20 horas

## Financial Sentiment Analysis
  - Este conjunto de dados reúne diversos textos sobre o mercado financeiro e categoriza cada texto em positivo, negativo e neutro.

## Sobre este projeto
  - Os principais pontos que serão avaliados:
    - Extração de dados
    - Manipulação de dados e criação de gráficos simples com o Pandas
    - Criar um modelo de predição
    - Apresentação dos resultados

## Preparação do ambiente
  - Para este projeto, acessem o link do dataset e logo abaixo cliquem em "Download". Caso você não tenha uma conta no Kaggle, crie uma e retorne para esse ponto para realizar o download. Descompacte o arquivo.
  - Este conjunto de dados está em inglês, use o Spacy e os demais dados auxiliares em inglês.
  - Caso demore demais para executar ou que ocorra estouro de memória, use somente 40% dos dados.

## Exercícios
  1. Construa as funções e a pipeline, separe os dados em treino e teste, execute a pipeline para classificar em positivo, negativo e neutro. Quais foram os valores de acurácia, precisão e sensitividade deste modelo? (3.0 pontos)
  
  2. Use o seu modelo para classificar os seguintes textos extraídos do site Financial Times. Faça uma tabela com o valor esperado e o valor obtido, e responda: houve divergência entre o esperado e o obtido? O que poderia ser feito para corrigir? (1.0 ponto)
    a. Central banks’ rate rises, geopolitical risk and slowing growth trigger investors’ stampede for safety. resultado esperado: [negativo]
    b. China opens up bond market in bid to woo foreign investors. resultado esperado: [neutro]
    c. HM Revenue & Customs says residents had £850bn in accounts overseas but it does not estimate if tax paid on this. resultado esperado: [negativo]
    d. Japan’s horrifying crop of data falsification is also encouraging. The scandals have emerged from a distinct new phase in the evolution of the country’s shareholder capitalism. resultado esperado: [negativo]
    e. Despite internal problems, the group continues to exert a tight grip on the US’s gun control debate. resultado esperado: [neutro]

  3. Faça uma análise exploratória, onde identifique as três empresas mais citadas e quantifique os níveis de positividade, negatividade e neutralidade dos textos sobre estas empresas. (3.0 pontos)
    a. Extraia de todos os textos as entidades, há quantas entidades? (0.6 pontos) b. Quantas entidades são empresas? (0.6 pontos) c. Quais são as três empresas mais citadas? (0.6 pontos) d. Faça uma tabela onde demonstre as três empresas mais citadas e o total de textos positivos, negativos e neutros de cada uma. (1.2 pontos)
  4. Faça gráficos a partir da tabela obtida acima. Descreva cada gráfico de forma que estivesse apresentando à diretoria dessas três empresas. (3.0 pontos)
