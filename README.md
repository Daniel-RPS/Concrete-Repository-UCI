# Concrete-Repository-UCI
Aplicando Machine Learning ao repositório da UCI para prever a resistência à compressão do concreto (PT-BR)

Fonte: http://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength

Bibliotecas utilizadas: pandas, matplotlib, matplotlib.pyplot, numpy, seaborn, sklearn.

Objetivo: Analisar o conjunto de dados de resistência à compressão do concreto, criar modelos de Machine Learning para prever a resistência à compressão e descobrir qual dos modelos utilizados apresenta melhor resultado

Descrição do conjunto de dados:
O conjunto de dados consiste em 1030 instâncias com 9 atributos e não possui valores ausentes. Existem 8 variáveis de entrada e 1 variável de saída. Sete variáveis de entrada representam a quantidade de matéria-prima (medida em kg / m³) e uma representa a idade (em dias). A variável alvo é a resistência à compressão do concreto medida em (MPa - Mega Pascal).

Foram utilizados 3 medidas (RMSE - Root Mean Square Error, R2, MAE - Mean Absolute Error) ara analisar os resultados gerados pelos modelos.

O dataset também foi útil para trabalhar com clusterização, prevendo a qual classe pertencerá cada compressão de concreto. Para isso, foi utilizado o método Elbow para determinar número ideal de clusters

Fontes:

1 - https://towardsdatascience.com/concrete-compressive-strength-prediction-using-machine-learning-4a531b3c43f3

2 - https://github.com/swethalahari/Determining-Concrete-Strength

3 - https://www.kaggle.com/pavanraj159/predicting-compressive-strength-of-concrete

4 - https://minerandodados.com.br/algoritmo-k-means-python-passo-passo/
