# ESP32/ESP8266 HTTP(S) channel sender
Simple example of how to send data from ESP32/ESP8266 boards to the flespi channel via http/https (with root CA/fingerprint).

## Prerequisites:

- Arduino IDE
- Hardware: [ESP8266](https://en.wikipedia.org/wiki/ESP8266) or [ESP32](https://en.wikipedia.org/wiki/ESP32) board

## Build Setup

### install additional board to Arduino IDE
[Arduino board project Howto](https://github.com/esp8266/Arduino/blob/master/README.md#installing-with-boards-manager)

Official Arduino IDE info on how to [install additional cores](https://www.arduino.cc/en/Guide/Cores)

### Select board
Arduino IDE: Tools -> Board -> Your board type (ESP32 Dev Module in my case [ESP32 Wrover-B](https://eu.mouser.com/new/espressif/espressif-esp32-wrover-b-module/))

### Test
- change credentials (credentials.h)
- compile the project and flash the board

## License
[MIT](https://github.com/flespi-software/ESP32-ESP8266_http_channel/blob/main/LICENSE) license.
