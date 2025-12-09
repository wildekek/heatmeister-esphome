# heatmeister-esphome
ESPHome firmware for the Heatmeister by [SDR Engineering](https://www.sdr-engineering.nl/webshop/index.php?route=product/product&product_id=50)

This (experimental) firmware was made because:
- Although the original firmware is great, I dislike running somebody elses firmware in my house.
- I wanted to import my existsing ambient temperature sensors from Home Assistant, so I have accurate room readings
- I wanted to import my [OpenTherm boiler sensors](https://github.com/wildekek/esphome-opentherm-templates).

## Warning!
- This firmware was reverse engineered without intricate knowledge of the board design nor consent of the creator. It may damage the board, void your waranty or cause unexpected behaviour. Do not compain to me, SDR Engineering or anyone else when you fry your hardware, flash this firmware at your own risk.
- There is no fan control algorithm in the firmware (yet). You'll need to do this yourself, or wait for me to do it when I have time. PR's are appreciated.

## Protip:
- The Heitmeister will only boot into bootloader mode when connected to USB. If you want to flash via OTA, you must connect a 12v power supply. The board seems very well engineered, but I would always recommend to never connect both USB and 12v at the same time.
