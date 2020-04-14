# ESPHome 6 shutters controller

Thanks to an ESP32 and ESPHome firmware, it is possible to drive 6 shutters with only 1 device. This controller is then integrated in Home Assistant domotic hub.

Device used is an ESP32 doit-devkit-v1.

For informations about ESPHome follow this link: https://esphome.io/index.html

Pull up resistors are needed to lower inputs inpedance, in order to avoid electrical effects using long cables. For inputs 34 to 39 it is required even because there are not internal pull ups resistors on these pins.

For shutter N.3 only one button was used (because there was not enough available pins). It works using long press to open and short press to close.
##
How to use: use this yaml code to create your ESPHome firmware: [esp32_six_shutters.yaml](https://github.com/Gio-dot/Six-shutters-ESP32-controller/blob/master/esp32_six_shutters.yaml)

Don't forget to adjust `open_duration` and `close_duration` at the end of this file according to open/close times of your shutters.
## Schematic
![Schematic](https://github.com/Gio-dot/Six-shutters-ESP32-controller/blob/master/img/ESP32-ESPhome-SHUTTERS_bb.png)

## Relays schematic detail
<img src="https://github.com/Gio-dot/Six-shutters-ESP32-controller/blob/master/img/ESP32-ESPhome-shutters%20relays_schem.png" width="400">

## A short test video
[![Watch the video](https://i9.ytimg.com/vi/tXZTDXVnUaA/mq2.jpg?sqp=CNmq1vQF&rs=AOn4CLDL7M_q2f9vk05kiKEQYxylnUY5xw)](https://youtu.be/tXZTDXVnUaA)

## Home Assistant Card
<img src="https://github.com/Gio-dot/Six-shutters-ESP32-controller/blob/master/img/2020-04-14%2015_17_17-Panoramica%20-%20Home%20Assistant.png" width="300">

## ESP32 
<img src="https://github.com/Gio-dot/Six-shutters-ESP32-controller/blob/master/img/ESP32-DOIT-DEVKIT-V1-Board-Pinout-30-GPIOs-Copy.png" width="300">
<img src="https://github.com/Gio-dot/Six-shutters-ESP32-controller/blob/master/img/ESP32%20IO.jpg" width="300">
<img src="https://github.com/Gio-dot/Six-shutters-ESP32-controller/blob/master/img/2020-04-14%2014_53_35-SeeKool%20ESP8266%20ESP32%20ESP-32S%20Scheda%20di%20Sviluppo%20per%20Arduino%2C%202.4GHz%20WiFi%20%2B%20Blue.png" width="300">

## Realy boards
<img src="https://github.com/Gio-dot/Six-shutters-ESP32-controller/blob/master/img/ESP32-DOIT-DEVKIT-V1-Board-Pinout-30-GPIOs-Copy.png" width="300">

