# Classificação com Árvores de Decisão

Este repositório contém dois notebooks Jupyter com aplicações de aprendizado supervisionado utilizando o algoritmo de árvore de decisão (`DecisionTreeClassifier`) da biblioteca scikit-learn.

Foram utilizados dois conjuntos de dados:


- **[Iris Dataset](https://archive.ics.uci.edu/dataset/53/iris)**: Classificação de flores em três espécies com base em quatro atributos morfológicos.
- **[Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)**: Classificação de tumores como benignos ou malignos com base em 30 atributos numéricos extraídos de imagens de biópsia.


As análises incluem:
- Preparação e divisão dos dados (treino/teste com estratificação);
- Análise exploratória com gráficos e matriz de correlação;
- Treinamento inicial dos modelos com parâmetros padrão;
- Avaliação com métricas de classificação;
- Aplicação de *cross-validation* com k=10;
- Otimização de hiperparâmetros via `GridSearchCV`.

### Arquivos

- `iris.ipynb`: Notebook com a análise do conjunto Iris.
- `breast_cancer.ipynb`: Notebook com a análise do conjunto Breast Cancer.
- [`relatorio.pdf`](./relatorio.pdf): Relatório final completo com descrição dos métodos, resultados e visualizações.

Para detalhes completos das análises e resultados, consulte o relatório em PDF.
