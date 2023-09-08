# Predição da Pontuação de Ansiedade em Jogadores Usando MLP

Essa análise de dados foi feita utilizando o conjunto de dados Online Gaming Anxiety Analysis, disponível no Kaggle. Meu objetivo foi treinar um modelo de machine learning usando uma Rede Neural MLP para prever a pontuação total de ansiedade com base em dados coletados de uma pesquisa relacionada a saúde dos jogadores.

## Pré-processamento de Dados

### Categorização da Pontuação de Ansiedade

- Foi usado o algoritmo KMeans para segmentar a pontuação de ansiedade em três categorias: baixa, média e alta.

### Tratamento dos Dados

- Para características numéricas: Preenchemos valores faltantes com a média e, em seguida, padronizamos os dados.
- Para características categóricas: Preenchemos valores faltantes com o valor "missing" e aplicamos a codificação OneHot.

### Modelo

- O modelo escolhido foi o MLPClassifier da biblioteca sklearn. Este é um modelo de rede neural do tipo MLP.

### Resultado e Visualização

- O modelo teve um ótimo desempenho, alcançando uma acurácia de 99.78%.
- Sua visualização foi através da Matriz de Confusão usando seaborn, mostrando uma clara distinção entre as previsões e os valores reais.

### Conclusão

- O modelo MLP mostrou-se eficiente na tarefa de prever a pontuação de ansiedade dos jogadores com base em suas respostas e características. O alto nível de acurácia e as métricas de avaliação indicam um bom desempenho do modelo nos dados de teste.
