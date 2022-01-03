Hardware
Requirements
Ra-02 LoRa module with SX1278 chip
433MHz antenna
STM32 microcontroller LoRa Ra-02 433MHz antenna
Wiring
The wire connections are like following:

||STM pin||	Module pin||
SPI MISO	MISO
SPI MOSI	MOSI
SPI CLK	CLK
a GPIO output (initially HIGH)	NSS
a GPIO output (initially HIGH)	RST
a GPIO input (EXTI - Rising edge)	DIO0
3.3v	3.3v
GND	GND
