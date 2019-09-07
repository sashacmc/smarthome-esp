# smarthome-esp
Eagle schemes for my esp8266 boards

## esp07_1w.*
Simple board to route 1-wire devices by esp07.
Fitted to standard phone socket.

## esp07_4PIO_6S_v2.*
My main smarthome esp07 board.
Provide:
* Four 220V outputs.
* Six dry contact (5V) inputs
* Two ext power (12V)
* Measure temperature and humidity by AM2302
* Measure illuminate by TSL2561

## esp07_co2.*
My first esp07 board
Provide:
* Measure temperature and pressure by BMP280
* Measuring CO2 level by MH-Z14

HAS BUGS WITH POWER CONSUMPTION FOR MH-Z14!!!

## esp07_ups.*
Board to control UPS by emulating power button pressing.
Has two power sources (from line and from UPS)
