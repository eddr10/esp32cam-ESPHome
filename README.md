YAML file for ESP32-CAM (Ai Thinker Model) for ESPHome and Home Assistant Integration. 

File is structured as next


1. General configuration for ESPHome and ESP32 Board
2. Network Configuration for Wifi, OTA and Home Assistant API
3. ESP32 Camera Settings (Usually using ESPHome example basics found on https://esphome.io/components/esp32_camera.html)


Configuration Variables also found on ESPHome settings, be wary of manufacturer recommendations on GPIOs or max_framerate

Image setting established on this project. 

Resolution: XGA, 4:3
Max frame rates: 15 fps 

Also added a Led component which ESP32CAM has included on board to create automation on Home Assistant. 




Device is flashed using ESPHome-flasher and ESPHome

https://github.com/esphome/esphome-flasher
https://esphome.io/guides/getting_started_hassio.html 
