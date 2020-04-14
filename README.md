# ESPHome 6 shutters controller

Thanks to an ESP32 and ESPHome firmware, it is possible to drive 6 shutters with only 1 device. This controller is then integrated in Home Assistant domotic hub.

Device used is an ESP32 doit-devkit-v1.

For informations about ESPHome follow this link: https://esphome.io/index.html

Pull up resistors are needed to lower inputs inpedance, in order to avoid electrical effects using long cables. For inputs 34 to 39 it is required even because there are not internal pull ups resistors on these pins.

For shutter N.3 only one button was used (because there was not enough available pins). It works using long press to open and short press to close.

## Schematic
![Schematic](https://github.com/Gio-dot/Six-shutters-ESP32-controller/blob/master/img/ESP32-ESPhome-SHUTTERS_bb.png)

## Relays schematic detail
<img src="https://github.com/Gio-dot/Six-shutters-ESP32-controller/blob/master/img/ESP32-ESPhome-shutters%20relays_schem.png" width="400">

## A short test video
[![Watch the video](https://i9.ytimg.com/vi/tXZTDXVnUaA/mq2.jpg?sqp=CNmq1vQF&rs=AOn4CLDL7M_q2f9vk05kiKEQYxylnUY5xw)](https://youtu.be/tXZTDXVnUaA)

## Home Assistant Card
<img src="https://github.com/Gio-dot/Six-shutters-ESP32-controller/blob/master/img/2020-04-14%2015_17_17-Panoramica%20-%20Home%20Assistant.png" width="180">


