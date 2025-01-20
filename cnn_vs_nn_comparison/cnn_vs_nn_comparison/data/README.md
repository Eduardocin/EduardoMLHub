# Conteúdo do arquivo /cnn_vs_nn_comparison/cnn_vs_nn_comparison/data/README.md

Este projeto utiliza conjuntos de dados disponíveis no Keras para comparar o desempenho entre uma Rede Neural Convolucional (CNN) e uma Rede Neural (NN) simples.

## Conjunto de Dados

O conjunto de dados utilizado neste projeto é o **CIFAR-10**, que contém 60.000 imagens coloridas de 32x32 pixels em 10 classes diferentes, com 6.000 imagens por classe. As classes são:

- Avião
- Automóvel
- Pássaro
- Gato
- Veado
- Cão
- Sapo
- Cavalo
- Navio
- Caminhão

## Origem dos Dados

O conjunto de dados CIFAR-10 pode ser acessado diretamente através da biblioteca Keras, facilitando o carregamento e a preparação dos dados para treinamento e validação.

## Uso dos Dados

Os dados serão utilizados para treinar dois modelos diferentes:

1. **Rede Neural Convolucional (CNN)**: Um modelo mais complexo que utiliza camadas convolucionais para extrair características das imagens.
2. **Rede Neural (NN)**: Um modelo mais simples que utiliza camadas densas para classificação.

Os resultados de desempenho de ambos os modelos serão comparados em termos de precisão e tempo de treinamento.