# heatmeister-esphome
Unofficial ESPHome firmware config for the Heatmeister by [SDR Engineering](https://www.sdr-engineering.nl/webshop/index.php?route=product/product&product_id=50)

I made this because:
- Although the original firmware is great, I dislike running somebody elses firmware in my house.
- I like to play around with control strategies
- I wanted to import my [OpenTherm boiler sensors](https://github.com/wildekek/esphome-opentherm-templates).

## Warning!
- This firmware was reverse engineered without intricate knowledge of the board design nor consent of the creator. It may damage the board, void your waranty or cause unexpected behaviour. Do not compain to me, SDR Engineering or anyone else when you fry your hardware, flash this firmware at your own risk. I have been running it without any issues for weeks without any issues.

## Flashing tip:
- The Heitmeister will only boot into bootloader mode when connected to USB. If you want to flash via OTA, you must connect a 12v power supply. The board seems very well engineered, but I would always recommend to never connect both USB and 12v at the same time.
