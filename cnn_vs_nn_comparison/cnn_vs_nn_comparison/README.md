# Conteúdo do arquivo /cnn_vs_nn_comparison/cnn_vs_nn_comparison/README.md

# Comparação entre Rede Neural Convolucional (CNN) e Rede Neural (NN)

Este projeto tem como objetivo comparar o desempenho de uma Rede Neural Convolucional (CNN) com uma Rede Neural (NN) simples utilizando um conjunto de dados disponível no Keras. O foco principal é entender como a arquitetura da rede influencia a precisão e a eficiência na classificação de imagens.

## Estrutura do Projeto

O projeto é organizado da seguinte forma:

- **data/README.md**: Contém informações sobre o conjunto de dados utilizado, incluindo detalhes sobre a origem dos dados e como eles podem ser utilizados.
  
- **notebooks/cnn_vs_nn_comparison.ipynb**: Este é o notebook principal do projeto. Ele inclui as etapas para carregar um conjunto de dados (como CIFAR-10 ou Fashion MNIST), preparar os dados, construir e treinar tanto uma CNN quanto uma NN simples, e comparar os resultados de desempenho entre os dois modelos.

- **requirements.txt**: Lista as dependências necessárias para o projeto, incluindo bibliotecas como TensorFlow, Keras e outras que podem ser necessárias para a execução do notebook.

## Instruções de Uso

1. Clone este repositório em sua máquina local.
2. Instale as dependências listadas em `requirements.txt` utilizando o comando:
   ```
   pip install -r requirements.txt
   ```
3. Abra o notebook `notebooks/cnn_vs_nn_comparison.ipynb` em um ambiente Jupyter Notebook ou Google Colab.
4. Siga as instruções no notebook para executar as etapas de carregamento de dados, treinamento dos modelos e comparação de resultados.

## Resultados Esperados

Ao final do projeto, espera-se observar que a CNN apresenta um desempenho superior em comparação à NN simples, especialmente em tarefas de classificação de imagens, devido à sua capacidade de extrair características espaciais mais complexas.