# Demo of Arduino Nano ESP32 in CircuitPython with OOCSI, DHT sensor, and 1602A LCD modules

This prototyping connects to the Internet with integrated wifi module and sends the humidity and temperature data to OOCSI, which is measured by DHT22 module, and at the mean time, the data is also displayed on the 1602A LCD module.

<br />

## Hardware

* Arduino Nano ESP32
* 1602A LCD module
* DHT22 module

<br />

## What's on LCD display

It shows the temperature and humidity value returned by the DHT22 module. <br />
But the lower part of first line is defected, so the first line only has upper part working.

![led demo](images/demo-lcd.jpg)

<br />

## Wiring

| 1602A LCD  |  Arduino Nano ESP32 | DHT22 |
| --- | --- | --- |
| SDA | A4 pin | |
| SCL | A5 pin | |
| GND | GND | - |
| VCC | 5V / VBUS | |
|| 3.3V | + |
|| D2 pin | out |

![wiring](images/demo-wiring.jpg)