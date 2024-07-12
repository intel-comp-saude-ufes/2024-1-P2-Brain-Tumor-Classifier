# 2024-1-P2-Brain-Tumor-Classifier
Trabalho 02 - Uso de CNN para a classificação de tumores cerebrais

O presente trabalho tem como objetivo a implementação e a análise de uma CNN capaz de classificar três tipos de tumores cerebrais (meningioma, glioma e pituitary) e ainda classificar um cérebro saudável. Para isso, utilizou-se a base pública *Brain tumors 256x256* presente no Kaggle. Mais informações sobre as imagens, incluindo onde baixá-las, estão disponíveis nesse [link](https://www.kaggle.com/datasets/thomasdubail/brain-tumors-256x256).



## Pré-requisitos

O arquivo `requirements.txt` contém todas as dependências necessárias para executar o código. Para instalar todas as dependências, basta digitar no terminal dentro da pasta raíz do projeto:
```
pip install -r requirements.txt
```

## Como executar

O código que implementa os classificadores está disponível no formato de jupyter-notebook. Para executar o código, basta clonar o repositório, fazer download do arquivo `.zip` com as imagens através desse [link](https://www.kaggle.com/datasets/thomasdubail/brain-tumors-256x256), garantir que o `.zip` esteja na mesma pasta raíz que o notebook e, na pasta raíz, digitar no terminal:

```
jupyter brain_tumor_classifier.ipynb
```

## Mais informações

Para mais informações sobre o projeto, assista ao vídeo feito pelos organizadores descrevendo a motivação por trás do projeto. O vídeo pode ser encontrado [aqui](https://www.youtube.com/watch?v=DArvKXh1C1o).
