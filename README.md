# Aplicativo de câmera📷
_Este é um aplicativo simples de câmera para dispositivos Android que permite ao usuário tirar uma foto usando a câmera do dispositivo ou escolher uma imagem da galeria. Ele exibe a foto selecionada na tela do aplicativo._

## ⚙️Funcionalidades:
__O aplicativo possui duas funcionalidades principais:__
- Tirar uma foto usando a câmera do dispositivo
- Escolher uma imagem da galeria de imagens do dispositivo

## 🛠️Como executar o aplicativo:
__Para executar o aplicativo em uma máquina local, siga as seguintes etapas:__

- Baixe e instale o Android Studio.
- Clone este repositório em seu computador.
- Abra o Android Studio e escolha a opção "Open an existing Android Studio project".
- Navegue até o diretório em que você clonou o repositório e selecione-o.
- Execute o aplicativo em um dispositivo Android ou em um emulador.

## ✔️Permissões:
__O aplicativo requer as seguintes permissões:__

- Permissão para acessar a câmera do dispositivo: `android.permission.CAMERA`                 
- Permissão para ler a galeria de imagens do dispositivo: `android.permission.READ_EXTERNAL_STORAGE`
                 
## ⚠️Vulnerabilidades:
__O aplicativo possui algumas vulnerabilidades, incluindo:__

Não há verificação para permissão concedida para acessar a câmera ou a galeria de imagens. Isso pode levar a violações de privacidade se o usuário não conceder permissão ou se o aplicativo acessar indevidamente as imagens do dispositivo.

A vulnerabilidade de injeção SQL pode ocorrer ao obter o caminho físico da imagem selecionada da galeria. É importante que seja feita uma validação e sanitização dos dados antes de executar uma consulta.

Não há tratamento de exceção adequado para casos em que a galeria de imagens ou a câmera não estejam disponíveis ou ocorra um erro ao obter a imagem selecionada. Isso pode levar a uma experiência de usuário ruim e ao encerramento inesperado do aplicativo.

## ✍️Autores

__- [@cemeterydriiver](https://www.github.com/cemeterydriiver)__
