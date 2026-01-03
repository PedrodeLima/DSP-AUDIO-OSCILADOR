# Projeto demonstração Osciladores e Envelope ADSR
## **(c) 2026 Pedro de Lima Freire, Analista de Sistemas*

## Formato de áudio
- 16-bits
- 44100hz
- 2 canais ( estéreo )
## Recursos
- Oscila em frequências entre 1 hz a 37585 hz ( notas -70 a 110 )
- As 4 fases ADSR de envelopamento ( Attack,Decay, Sustain, Release )
- Pitch
- Pan , Balanceamento do sinal entre os 2 lados do fone.
- Formatos de onda:
     - Seno
     - Qaudrada
     - Triângulo
     - Serra ou Serrote
     - Chiado
### Dependência para o teste
biblioteca wrapper directx8 para VB6
arquivo dx8vb.dll
user o comando, em modo administrador:

**Regsv32 dx8vb.dll**

## Código-Fonte
### Linguagem VB6
### Sistema Operacional Windows.
- Versão com uso de DirectX, que é a mesma disponibilizada no teste.
- Versão utilizando a API WIN32 da família __WaveOut__
- Preço: R$ 6500

### Linguagem C+
### Sistema Operacional Windows
- Versão utilizando a API WIN32 da família __WaveOut__
- Preço: R$ 5500

### Sistema Operacional Linux (Pc, Raspberry e demais embarcados compatíveis)
- Versão utilizando a biblioteca __aSound__ da biblioteca __ALSA__

__As Biliotecas DirectX, WaveOut e aSound são usadas apenas para a transmissão do sinal para o dispositivo de áudio. Essas 3 bibliotecas são dos sistemas operacionais e não pertencem a terceiros.__
__Todo o processamento DSP e modulação feito por algoritmos de minha autoria. não há dependências a outras bibliotecas de terceiros.__

### Contato para acquisição / compra dos códigos fonte:
__PedroLFreire2@hotmail.com ou SnesFanRemix@gamil.com__
