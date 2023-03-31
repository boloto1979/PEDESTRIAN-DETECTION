# Detector de pedestres utilizando HOG

Este é um projeto de detecção de pedestres em vídeo utilizando o algoritmo HOG (Histogram of Oriented Gradients) em conjunto com a técnica de SVM (Support Vector Machines). O código foi implementado em Python, utilizando as bibliotecas OpenCV e imutils.

## Como funciona

O algoritmo HOG é uma técnica utilizada para detecção de objetos em imagens. Ele funciona criando um histograma da orientação dos gradientes em uma região da imagem e utilizando essa informação para identificar objetos. Já o SVM é um algoritmo de aprendizado de máquina que utiliza um conjunto de dados de treinamento para classificar novos exemplos.

O detector de pedestres utilizado neste projeto foi pré-treinado com um grande conjunto de dados e já é capaz de identificar com precisão a presença de pedestres em imagens. O código utiliza esse detector para analisar quadro a quadro um vídeo, identificando regiões onde há a presença de pedestres e desenhando retângulos sobre essas regiões.

## Como utilizar

Para utilizar este detector de pedestres em um vídeo, basta executar o código em um ambiente Python com as bibliotecas OpenCV e imutils instaladas. É necessário fornecer o caminho para o vídeo que será analisado na linha `cap = cv2.VideoCapture('CodeWisdom_Video.mp4')`. Certifique-se de que o arquivo de vídeo está localizado no mesmo diretório do código.

Ao executar o código, será aberta uma janela com o vídeo sendo analisado, onde os retângulos indicando a presença de pedestres serão desenhados em tempo real. Pressione a tecla "q" para encerrar a execução do código e fechar a janela do vídeo.

## Créditos

Este projeto foi criado com base no tutorial "Pedestrian Detection OpenCV Python | HOG descriptor and SVM (Support Vector Machine)" do canal Murtaza's Workshop - Robotics and AI.

