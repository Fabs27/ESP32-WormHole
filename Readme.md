Função	Pino ESP32

Display TFT

TFT_CS	10
TFT_RST	9
TFT_DC	8
TFT_MOSI	23
TFT_SCK	18

SD Card

SD_CS	5
SD_MISO	19
SD_MOSI	23
SD_SCK	18

Botões

BTN_UP	32
BTN_DOWN	33
BTN_LEFT	25
BTN_RIGHT	26
BTN_SELECT	27
BTN_BACK	14

Módulo NRF24

NRF_CE	4
NRF_CSN	5
NRF_MOSI	23
NRF_MISO	19
NRF_SCK	18

Porta Serial

TX	1
RX	3

Estrutura Completa do Projeto ESP32

Diretório	Conteúdo

ProjetoESP32/	Raiz do projeto

├── ProjetoESP32.ino	Arquivo principal

├── GPIO/	Diretório para arquivos GPIO

│ ├── tft_display.c	Implementação do display

│ ├── tft_display.h	Cabeçalho do display

├── APPS/	Diretório para aplicativos

│ ├── KeyCopy/	Diretório do aplicativo KeyCopy

│ │ ├── key_copy_app.c	Implementação do aplicativo

│ │ ├── key_copy_app.h	Cabeçalho do aplicativo

├── SD Card/	Diretório para arquivos do SD

│ ├── apps/	Diretório de aplicativos no SD

│ │ ├── KeyCopy/	Diretório do KeyCopy no SD

│ │ │ ├── key_copy_config.txt	Configuração do KeyCopy no SD
