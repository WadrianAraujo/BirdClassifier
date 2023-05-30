# Aplicativo de Classificação de Pássaros

Este é um aplicativo Android desenvolvido em Kotlin que utiliza o TensorFlow Lite para realizar a classificação de pássaros. O modelo de classificação utilizado é o [aiy/vision/classifier/birds_V1/3](https://tfhub.dev/google/lite-model/aiy/vision/classifier/birds_V1/3) disponibilizado pelo TensorFlow Hub.

## Funcionalidades

O aplicativo oferece as seguintes funcionalidades:

1. Classificação de Pássaros: O usuário pode capturar uma imagem de um pássaro usando a câmera do dispositivo ou selecionar uma imagem existente da galeria. Em seguida, o aplicativo utiliza o modelo TensorFlow Lite para classificar o pássaro na imagem e exibe o resultado com a espécie identificada.

## Requisitos do Sistema

- Dispositivo Android com a versão mínima X.X.X
- Câmera para captura de imagens (opcional)

## Configuração do Projeto

1. Clone este repositório em seu ambiente de desenvolvimento:

```shell
git clone https://github.com/WadrianAraujo/BirdClassifier.git
```

2. Abra o projeto no Android Studio.

3. Certifique-se de ter a versão correta do Kotlin instalada.

4. Verique se o arquivo `build.gradle` do módulo do aplicativo esta com as seguintes dependências:

```groovy
dependencies {
    // ...
    implementation 'org.tensorflow:tensorflow-lite:2.5.0'
    implementation 'org.tensorflow:tensorflow-lite-gpu:2.5.0'
}
```

5. Execute o aplicativo no dispositivo ou emulador Android.

## Uso do Aplicativo

1. Ao abrir o aplicativo, você será apresentado à tela principal.

2. Para classificar um pássaro usando a câmera:
   - Clique no botão "Câmera".
   - Enquadre o pássaro na tela e clique no botão de captura.
   - O aplicativo realizará a classificação do pássaro e exibirá o resultado.

3. Para classificar uma imagem existente:
   - Clique no botão "Galeria".
   - Selecione a imagem do pássaro desejado.
   - O aplicativo realizará a classificação do pássaro e exibirá o resultado.

## Contribuição

As contribuições para aprimorar este aplicativo são bem-vindas. Se você encontrar problemas, bugs ou tiver sugestões de melhorias, fique à vontade para abrir uma [issue](https://github.com/seu-usuario/nome-do-repositorio/issues) ou enviar um [pull request](https://github.com/seu-usuario/nome-do-repositorio/pulls).

## Agradecimentos

- TensorFlow Lite: https://www.tensorflow.org/lite
- TensorFlow Hub: https://tfhub.dev/

Esperamos que este aplicativo seja útil para classificar e identificar diferentes espécies de páss
