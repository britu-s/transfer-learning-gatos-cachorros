# Projeto: Transfer Learning com MobileNetV2 

Este projeto aplica o conceito de **Transfer Learning** usando o modelo pré-treinado **MobileNetV2** para classificar imagens de **gatos e cachorros**.

##  Dataset

Usamos o dataset `cats_and_dogs_filtered`, disponível publicamente:

- [Link do Dataset](https://storage.googleapis.com/mledu-datasets/cats_and_dogs_filtered.zip)

O conjunto contém:

- 2000 imagens para treino (1000 de cada classe)
- 1000 imagens para validação

##  Modelo

O modelo foi construído com:

- **MobileNetV2** (pré-treinada no ImageNet)

A acurácia final de validação foi de aproximadamente **96%** após 3 épocas.

## Execução

O projeto foi desenvolvido e testado no **Google Colab**, com Python e TensorFlow.

##  Resultado

O modelo treinado foi salvo como: `mDesafio1_ML_Gatos_Cachorros.ipynb`

## Autor

Alberto Brito  
Projeto desenvolvido como desafio da DIO 
