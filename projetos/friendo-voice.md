# Friendo Voice

O Friendo surgiu para reunir um grupo de amigos em salas de texto e voz. Dá para entrar numa chamada, transmitir um jogo e assistir à tela de outra pessoa na mesma sala. Cada pessoa também pode personalizar o avatar e o perfil.

## Como é feito

- **Cliente web.** TypeScript para chat, canais, chamadas, perfis e personalização.
- **Windows.** Go e WebView2 para a interface, com captura nativa de janelas e monitores e codificação de vídeo pelo FFmpeg.
- **Android.** Java e WebView, com um serviço de chamada e seleção de saída de áudio entre alto-falante e fone.
- **Tempo real.** Spacebar para mensagens e presença, LiveKit para voz, vídeo e transmissão de tela.

O projeto é de uso privado. A capa do perfil usa o símbolo e a paleta do Friendo Voice.

[Voltar ao perfil](../README.md)
