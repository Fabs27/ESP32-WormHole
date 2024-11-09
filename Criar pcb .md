15 Pinos GPIO Disponíveis
PA12

PA13

PA14

PA15

PB0

PB1

PB2

PB3

PB4

PB5

PB12

PB13

PB14

PB15

PC0

Conexões para os Componentes Principais
Microcontrolador Principal: STM32F411

VDD (3.3V): Alimentação

GND: Terra

PA0: Emissor IR

PA1: Receptor IR

PA2 (USART2_TX): Comunicação com ATmega328P (TX)

PA3 (USART2_RX): Comunicação com ATmega328P (RX)

PA4 (SPI1_NSS): CS do CC1101

PA5 (SPI1_SCK): SCK do CC1101

PA6 (SPI1_MISO): MISO do CC1101

PA7 (SPI1_MOSI): MOSI do CC1101

PA9 (USB D+): Conectividade USB Tipo-C

PA11 (USB D-): Conectividade USB Tipo-C

PB6 (I2C1_SCL): SCL do LCD 128x64

PB7 (I2C1_SDA): SDA do LCD 128x64

PB8: Botões Táteis

PB9: Botões Táteis

PB10: Botões Táteis

PB11: Botões Táteis

Microcontrolador Secundário: ATmega328P

VCC (5V ou 3.3V): Alimentação

GND: Terra

TX (PD1): Conectado ao RX do STM32F411 (PA3)

RX (PD0): Conectado ao TX do STM32F411 (PA2)

Módulo Sub-1 GHz: CC1101

VCC (3.3V): Alimentação

GND: Terra

CS: Conectado ao PA4 do STM32F411

SCK: Conectado ao PA5 do STM32F411

MISO: Conectado ao PA6 do STM32F411

MOSI: Conectado ao PA7 do STM32F411

Módulo NFC/RFID: MFRC522

VCC (3.3V): Alimentação

GND: Terra

CS: Conectado ao PA4 do STM32F411 (pode ser compartilhado com o CC1101 via um multiplexador ou gerenciar via software)

SCK: Conectado ao PA5 do STM32F411

MISO: Conectado ao PA6 do STM32F411

MOSI: Conectado ao PA7 do STM32F411

Display LCD 128x64

VCC (3.3V): Alimentação

GND: Terra

SCL: Conectado ao PB6 do STM32F411

SDA: Conectado ao PB7 do STM32F411

Emissor e Receptor IR

VCC (3.3V): Alimentação

GND: Terra

Emissor Data: Conectado ao PA0 do STM32F411

Receptor Data: Conectado ao PA1 do STM32F411

Porta USB Tipo-C

VCC (5V): Alimentação (para carregar a bateria)

GND: Terra

USB D+: Conectado ao PA9 do STM32F411

USB D-: Conectado ao PA11 do STM32F411

Bateria Li-Po 1000mAh

VCC: Conectado ao circuito de carregamento e ao VDD do STM32F411

GND: Terra

Botões Táteis

VCC (3.3V): Alimentação

GND: Terra

Data: Conectados aos pinos GPIO PB8 - PB11 do STM32F411