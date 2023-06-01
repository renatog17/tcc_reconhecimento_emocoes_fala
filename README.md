# Reconhecimento de Emoções em Áudios Utilizando Coeficientes MFCC

O trabalho intitulado **"Reconhecimento de Emoções em Áudios Utilizando Coeficientes MFCC"** teve como objetivo desenvolver um sistema automatizado para identificar emoções expressas em áudios. O estudo utilizou uma abordagem baseada em redes neurais convolucionais (CNN) e a biblioteca TensorFlow para implementação do modelo de aprendizado de máquina.

## Implementação

A implementação do sistema foi realizada em Python, aproveitando a ampla gama de bibliotecas disponíveis para processamento de sinais e aprendizado de máquina. Para a extração dos coeficientes MFCC dos áudios, a biblioteca Librosa foi utilizada, permitindo obter representações compactas e discriminantes das características acústicas presentes nos áudios.

Os áudios utilizados no estudo foram obtidos do YouTube, sendo necessário o pré-processamento e a organização dos dados antes da extração dos coeficientes MFCC. A biblioteca Pandas foi empregada para manipulação e estruturação dos dados dos áudios, facilitando seu armazenamento e posterior uso.

## Modelo de Aprendizado de Máquina

Após a extração dos coeficientes MFCC, o modelo de aprendizado de máquina foi implementado utilizando a biblioteca TensorFlow, que oferece suporte para a criação de redes neurais convolucionais. As redes neurais convolucionais são especialmente adequadas para o processamento de dados sequenciais, como áudios, devido à sua capacidade de capturar padrões espaciais e temporais.

Durante o treinamento, amostras de áudio previamente rotuladas foram utilizadas para ensinar o modelo a reconhecer as emoções presentes nos áudios. Métricas de desempenho, como acurácia, foram utilizadas para avaliar a precisão do sistema.
## Como usar
