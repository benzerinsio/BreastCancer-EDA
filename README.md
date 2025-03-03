# 🎗️ Análise para Detecção de Câncer de Mama  
*Projeto de Análise Exploratória de Dados (EDA) - Felipe V. Sousa*

Bem-vindo(a)! Este repositório apresenta uma **Análise Exploratória de Dados (EDA)** no conjunto de dados de câncer de mama, explorando características clínicas e sua relação com o diagnóstico.

🔗 [Visualizar o Notebook](https://github.com/benzerinsio/BreastCancer-EDA/blob/main/EDA-BreastCancer.ipynb)

## 🎯 Objetivo da Análise

Analisar um conjunto de dados com características clínicas de tumores (como `Radius`, `Area` e `Concavity`) e o diagnóstico (`Diagnosis`), para entender distribuições, identificar padrões e explorar associações que influenciam a classificação entre benigno e maligno, gerando insights úteis e preparando uma base para futuros modelos preditivos.

## 📊 Fonte de Dados

Os dados vêm do arquivo `breast_cancer.csv` (UCI Machine Learning Repository), contendo 569 registros de tumores.

## 🛠️ Bibliotecas Utilizadas

- **Pandas**: Manipulação e análise de dados.  
- **NumPy**: Cálculos numéricos e operações matemáticas.  
- **Seaborn**: Visualizações estatísticas como boxplots e scatters.  
- **Matplotlib**: Criação de gráficos lado a lado e pairplots.

## 💬 Conclusão

Este projeto realizou uma **Análise Exploratória de Dados (EDA)** no dataset de câncer de mama, identificando padrões como a tendência de maior tamanho (`Area`, `Radius`) e irregularidade (`Concavity`, `Concave_Points`) em tumores malignos. A alta multicolinearidade entre variáveis foi destacada como ponto de atenção. Apesar de alguma sobreposição entre classes, a separação evidente sugere que esse dataset é uma base promissora pra Machine Learning, com potencial pra alta precisão na classificação de diagnósticos.