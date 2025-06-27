# Previsão de Preços de Ações do Google com LSTM

Este projeto demonstra a aplicação de Redes Neurais de Memória de Longo Prazo (LSTM - Long Short-Term Memory) para prever os preços de abertura das ações do Google (GOOGL). Utiliza dados históricos para treinar um modelo que tenta aprender os padrões temporais e realizar previsões sobre o valor das ações.

## Visão Geral

O modelo LSTM é uma arquitetura de rede neural recorrente (RNN) que se destaca em tarefas de previsão de séries temporais, como dados financeiros, devido à sua capacidade de aprender dependências de longo prazo nos dados. Neste projeto, o modelo é treinado com o preço de abertura diário das ações do Google de 2012 a 2016 e, em seguida, é usado para prever os preços para um período de teste em 2017.

## Estrutura do Projeto

* `LSTM.ipynb`: O notebook Jupyter que contém todo o código Python para preparação de dados, construção do modelo, treinamento e visualização dos resultados.
* `Google_Stock_Price_Train.csv`: Arquivo CSV contendo os dados históricos de preços de ações do Google para treinamento (2012-2016).
* `Google_Stock_Price_Test.csv`: Arquivo CSV contendo os dados históricos de preços de ações do Google para teste (Janeiro de 2017).

## Tecnologias Utilizadas

* **Python 3**
* **TensorFlow/Keras**: Para a construção e treinamento da rede neural LSTM.
* **Pandas**: Para manipulação e análise de dados.
* **NumPy**: Para operações numéricas.
* **Matplotlib**: Para visualização de dados e resultados.
* **Scikit-learn**: Para pré-processamento de dados (MinMaxScaler).


## Resultados

O notebook `LSTM.ipynb` gerará um gráfico comparando os preços reais das ações do Google com os preços previstos pelo modelo LSTM para o período de teste. A linha vermelha representa os preços reais e a linha azul representa as previsões.


![Image](https://github.com/user-attachments/assets/62e279d1-e77e-4776-a611-9c9f638ae958)
