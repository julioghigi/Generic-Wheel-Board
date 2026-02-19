# Generic Wheel Board

A _Generic Wheel Board_ é um produto da __GhiMa__ que fornece toda a eletrônica necessária para montagem de volantes _DIY_!

Com um ESP32S3 como cérebro, a placa fornece 32 entradas programáveis, comunicação USB, Bluetooth, WiFi, gerenciamento de bateria e USB HUB integrado permitindo conexão de telas e outros dispositivos USBs.

_Features_:
- 32 entradas separadas em 23 conectores, sendo 15 conectores de 2 pinos (GND e IN), 3 de 3 pinos (VCC, IN E GND), 4 conectores de 4 pinos com descrição de encoder (GND, IN, IN E IN) e 1 conector de 4 pinos com descrição serial (GND, IN, IN e VCC).
- Telemetria SimHub via USB e WiFi (requer _Dongle_) para saída de leds progrmáveis.
- Joystick HID via USB ou Bluetooth.
- Chip USB-SERIAL dedicado para maior estabilidade de comunicação.
- 2 entradas USBs disponíveis para conexão de telas (VoCore ou USBD480) ou qualquer outro dispositivo USB.
- Circuito de gerenciamento de bateria para volantes sem fio, com proteção _over-current_, _over-voltage_, _under-voltage_ e todo o necessário para correto carregamento de baterias de 1 célula (4.2V máx.).

As 32 entradas podem ser programadas como: 
- Entrada digital (botão)
- Entrada analógica (Eixos)
- Entrada Encoder (DT, CLK e SW)
- Saída para LED (Telemetria SimHub)

## Visão geral da placa

<img width="1204" height="696" alt="Descricao" src="https://github.com/user-attachments/assets/f77e24b3-e3bb-454d-be8b-674cee9d6202" />

## Integração com SimHub

A placa é reconhecida automáticamente no SimHub como um _Device_, permitindo fácil personalização dos leds e telas integradas.

<img width="1403" height="731" alt="SimHub" src="https://github.com/user-attachments/assets/28fcd861-b1ec-4cbc-b829-e9400c1aae62" />

## Software para personalização

A placa possui software próprio para personalização das entradas e _features_.

<img width="580" height="641" alt="Software" src="https://github.com/user-attachments/assets/d6c7f2ee-143d-40c6-b10e-7aefc4084dc9" />

## Futuro
Diversos updates serão implementados, bem como toda documentação de suporte para uso.

## Redes sociais
Siga-nos no Instagram para ficar por dentro de todas as novidades!

![QRCode_insta](https://github.com/user-attachments/assets/6463d8b0-38e6-4db5-9cde-66a5f403ca8c)
