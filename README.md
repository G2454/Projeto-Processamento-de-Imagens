# Classificação de Grãos de Café Utilizando ResNet50 com Transfer Learning e Fine-Tuning

## Equipe

Guilherme Yuuki Sumita

## Descrição da Abordagem Utilizada

Este projeto implementa um sistema de classificação de grãos de café usando aprendizado profundo, seguindo uma abordagem moderna baseada em Transfer Learning com ResNet50 pré-treinada no ImageNet.

## Link para o repositório com o código (sem o dataset) e o vídeo de apresentação. 

[Repositório GitHub]()

[Vídeo]()


## Link para o dataset utilizado

[Coffee Bean Dataset Resized](https://www.kaggle.com/datasets/gpiosenka/coffee-bean-dataset-resized-224-x-224)

## Acurácia Obtida

- Acurácia Geral: 86.5%

## Precisão por Classe

| Classe | Precisão|
| ----------- | ----------- |
| Dark | 0.84      |
| Green| 0.96        |
| Light| 0.86       |
| Medium| 0.82        |

## Recall por Classe

| Classe | Recall|
| ----------- | ----------- |
| Dark | 0.82      |
| Green| 0.88        |
| Light| 0.96       |
| Medium| 0.80        |

## F1-score por Classe

| Classe | Precisão|
| ----------- | ----------- |
| Dark | 0.83      |
| Green| 0.92        |
| Light| 0.91       |
| Medium| 0.81        |

## Instruções de uso

1. Faça o download do projeto fornecido pelo professor [link](https://drive.google.com/file/d/1N5HlPZQfCDMWfPGNgnoPt7g8s0pZK8TH/view?usp=sharing)
2. Na pasta Colab Notebooks no seu Google Drive, crie uma pasta chamada "VC"
3. Dentro da pasta "VC", coloque a pasta extraída
4. Abra a pasta extraída, vá em "Módulos, depois "Classificadores" e substitua o arquivo "cnn_treino.py" por esse novo [link](https://drive.google.com/file/d/12Jjvsmg73Ws2BUw9fD6XHyJm6bgE5U8S/view?usp=sharing)
5. Após todos esses passos, volte para a raiz do projeto "Classificacao_CNN" e abra o arquivo "janela_principal.ipynb" no Google Colab
6. Ao executar o script no Google Colab, faça o treinamento, digitando a opção 1 (Em torno de uma hora e trinta minutos pela CPU do Google Colab)
7. Assim que finalizar, digite a opção 2 para testar o modelo.
