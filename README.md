
# Projeto demonstração Osciladores e Envelope ADSR
## **(c) 2026 Pedro de Lima Freire, Analista de Sistemas*

## Formato de áudio
- 16-bits
- 44100hz
- 2 canais ( estéreo )
## Algoritmos
- Oscilador de frequências entre 1 hz a 37585 hz ( notas -70 a 110 )
- Modula as 4 fases ADSR de envelopamento ( Attack,Decay, Sustain, Release )
- Pitch
- Pan , Balanceamento do sinal entre os 2 lados do fone.
- Modula o sinal de acordo com o formatos de onda:
     - Seno
     - Quadrada
     - Triângulo
     - Serra ou Serrote
     - Chiado

![rrr1](https://github.com/PedrodeLima/DSP-AUDIO-OSCILADOR/blob/main/tela.png)
### INSTALAR DLL binárias Windows vista em diante
dll directx8 para VB6
arquivo dx8vb.dll
use o comando, em modo administrador:

**Regsv32 dx8vb.dll**

## Código-Fonte
### Linguagem VB6
### Sistema Operacional Windows.
- Versão com uso de DirectX, que é a mesma disponibilizada no teste.
- Versão utilizando a API WIN32 da família __WaveOut__
- Preço: R$ 6500
![rrr1](https://github.com/PedrodeLima/DSP-AUDIO-OSCILADOR/blob/main/tela2.png)
### Linguagem C+
### Sistema Operacional Windows
- Versão utilizando a API WIN32 da família __WaveOut__
- Preço: R$ 5500

### Sistema Operacional Linux (Pc, Raspberry e demais embarcados compatíveis)
- Versão utilizando a biblioteca __aSound__ da biblioteca __ALSA__
- 
![rrr1](https://github.com/PedrodeLima/DSP-AUDIO-OSCILADOR/blob/main/tela3.png)

__As Biliotecas DirectX, WaveOut e aSound são usadas apenas para a transmissão do sinal para o dispositivo de áudio. Essas 3 bibliotecas são dos sistemas operacionais e não pertencem a terceiros.__
__Todo o processamento DSP e modulação feito por algoritmos é de minha autoria. não há dependências a outras bibliotecas de terceiros.__

### Contato para acquisição / compra dos códigos fonte:
__PedroLFreire2@hotmail.com ou SnesFanRemix@gmail.com__

[![ver  vídeo](https://upload.wikimedia.org/wikipedia/commons/thumb/0/09/YouTube_full-color_icon_%282017%29.svg/960px-YouTube_full-color_icon_%282017%29.svg.png?20240107144800)](https://www.youtube.com/watch?v=QpN9ca3yg_4&t=14s)
