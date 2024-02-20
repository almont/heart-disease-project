# Projeto de Doença Cardíaca

Este projeto utiliza vários modelos de aprendizado de máquina para prever a presença de doença cardíaca em pacientes.

## Código

O código principal está no arquivo `heart_disease_project.ipynb`. Ele treina vários modelos em um conjunto de dados de treinamento e, em seguida, avalia cada modelo usando a métrica ROC AUC.

O código faz o seguinte:

1. Limpa o gráfico atual usando `plt.clf()`.
2. Para cada modelo em uma lista de modelos:
    - Treina o modelo no conjunto de treinamento.
    - Faz previsões no conjunto de teste.
    - Calcula a pontuação ROC AUC.
    - Imprime a pontuação ROC AUC.
    - Calcula a curva ROC.
    - Plota a curva ROC.
3. Plota uma linha cinza diagonal (a "linha de base").
4. Adiciona rótulos aos eixos x e y.
5. Adiciona uma legenda.
6. Adiciona um título.
7. Exibe o gráfico.

## Como executar

Para executar o projeto, você precisará do Jupyter Notebook instalado. Abra o arquivo `heart_disease_project.ipynb` no Jupyter Notebook e execute todas as células.

## Dependências

Este projeto depende das seguintes bibliotecas Python:

- matplotlib
- numpy
- sklearn