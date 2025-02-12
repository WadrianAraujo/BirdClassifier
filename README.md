# Aplicativo de Classificação de Pássaros

Este é um aplicativo Android desenvolvido em Kotlin que utiliza o TensorFlow Lite para realizar a classificação de pássaros. O modelo de classificação utilizado é o [aiy/vision/classifier/birds_V1/3](https://tfhub.dev/google/lite-model/aiy/vision/classifier/birds_V1/3) disponibilizado pelo TensorFlow Hub.

<p align="center">
   <img src="https://github.com/WadrianAraujo/WadrianAraujo/blob/1a7ae957bcb7a89d6a49f30cfa7affa1db3810a0/ImagesForReadMe/BirdClassifier/BirdClassifierHome2.jpg" width="300" style="margin-left: 20px;:"> 
   <img src="https://github.com/WadrianAraujo/WadrianAraujo/blob/74b4f135f5a61fa44972d04543b503d0eedd4733/ImagesForReadMe/BirdClassifier/BirdClassifierHome1.jpg" width="300" style="margin-right: 20px;">
</p>

## Funcionalidades

O aplicativo oferece as seguintes funcionalidades:

1. Classificação de Pássaros: O usuário pode capturar uma imagem de um pássaro usando a câmera do dispositivo ou selecionar uma imagem existente da galeria. Em seguida, o aplicativo utiliza o TensorFlow Lite para classificar o pássaro da imagem e exibe o resultado com a espécie identificada.

## Requisitos do Sistema

- Dispositivo Android com a versão mínima 7.0.1
- Câmera para captura de imagens (opcional)

## Uso do Aplicativo

1. Ao abrir o aplicativo, você será apresentado à tela principal.

2. Para classificar um pássaro usando a câmera:
   - Clique no botão "Câmera".
   - Enquadre o pássaro na tela e clique no botão de captura.
   - O aplicativo realizará a classificação do pássaro e exibirá o resultado.
   - Clique no resultado para ser redirecionado para uma pesquisa no google com o nome do passaro

3. Para classificar uma imagem existente:
   - Clique no botão "Galeria".
   - Selecione a imagem do pássaro desejado.
   - O aplicativo realizará a classificação do pássaro e exibirá o resultado.
   - Clique no resultado para ser redirecionado para uma pesquisa no google com o nome do passaro
     
## Contribuição

As contribuições para aprimorar este aplicativo são bem-vindas. Se você encontrar problemas, bugs ou tiver sugestões de melhorias, fique à vontade para abrir uma issue ou enviar um pull request.
