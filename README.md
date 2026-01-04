# HeatMeister ESPHome
Unofficial ESPHome firmware for the HeatMeister by [SDR Engineering](https://www.sdr-engineering.nl/webshop/index.php?route=product/product&product_id=50).

I have no official affiliation whatsover with SDR Engineering, but I highly recommend their products. Go buy one!

### Why does this exist
- Although the original firmware is great, I prefer running open source firmware in my house.
- I like to play around with control strategies
- I wanted to import my [OpenTherm boiler sensors](https://github.com/wildekek/esphome-opentherm-templates).

## Getting started
1. Download the latest release
2. Use a USB-C cable to connect your HeatMeister to your PC
3. Open Chrome (or another browser that support WebSerial) and flash the firmware using [ESPHome WEB](https://web.esphome.io/)
4. Connect your WiFi to the "heatmeister" access point, password '12345678'
5. Fill in your WiFi credentials.


### Flashing tip:
- The HeatMeister will only boot into bootloader mode when connected to USB. If you want to flash via OTA, you must connect a 12v power supply. The board seems very well engineered, but I recommend to never connect both USB and 12v at the same time.

> ## ⚠️ Warning 
> This firmware was reverse engineered without intricate knowledge of the board design nor consent of the creator. It may damage the board, void your waranty or cause unexpected behaviour. Do not compain to me, SDR Engineering or anyone else when you fry your hardware, flash this firmware at your own risk. I have been running it without any issues for weeks without any issues.
