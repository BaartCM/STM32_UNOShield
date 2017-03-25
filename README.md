# STM32_UNOShield

This is a design for an adapter to mount a 'blue pill' stm32f103 and connect it to a standard UNO form factor TFT shield from ebay, aliexpress etc.

tft_adapter_1 has a double row of header pins either side of the blue pill to attach jumper wires to and also 3.3V, 5V and ground pins to power sensors etc.

tft_sdapter_2 is more specialised. It has a row of 6 push butto switches which can be fitted if desired and a row of header pins to connect to 10 different pins on the blue pill, 2 analog and 8 digital including the 8 used for push buttons if fitted. it also has provision for a backup battery for the rtc if desired.

Both boards have a terminal block to apply external power, a 5V and 3.3V regulator.

The TFT uses PA0 .. PA7 for DATA and PA5 .. PA9 for CTRL

The SD card reader uses SPI2 ie PB12 .. PB15
