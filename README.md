<p align="center">
<b>Adventures witha  tiny IPS display   </b><br>
<br><br>
<br>🐦 <a href="https://twitter.com/mkmeorg">Twitter</a>
| 📺 <a href="https://www.youtube.com/mkmeorg">YouTube</a>
| 🌍 <a href="http://www.mkme.org">mkme.org</a><br>
<br>
Support this project and become a patron on <a href="https://www.patreon.com/EricWilliam">Patreon</a>.<br>
Chat: <a href="https://discord.gg/j9S4Fgv">Discord</a></b>!
</p>



# 240x240_IPS_ST7789
ST7789 240x240 IPS Display for Electronics Projects 

Arduino Nano

<img src="https://github.com/MKme/240x240_IPS_ST7789/blob/main/ref/s-l1600.jpg" width="400"/>

ESP

<img src="https://github.com/MKme/240x240_IPS_ST7789/blob/main/ref/esp8266-nodemcu-st7789-spi-tft-circuit.png" width="400"/>

Buy the 240x240 IPS display on eBay here: https://ebay.us/9oGXxW

Cool tutorial: https://www.youtube.com/watch?v=EGpuhVnUhNo

Pin Descriptions:
		
| PIN No	| Symbol | 	Description | 
|-------------|------------------|----------------|
| 1	| GND	| Ground 
| 2	| VCC	| Power 3.3V
| 3	| SCL	| Serial clock pin.
| 4	| SDA	| Serial data input
| 5	| RES	| LCM Reset pin This pin is reset signal input. When the pin is low, initialization of the chip is executed. Keep this pin pull high during normal operation.
| 6	| DC	| Data/Command Control
| 7	| BLK	| Backlight control pin


The ST7789 display module shown in project circuit diagram has 7 pins: (from right to left): GND (ground), VCC, SCL (serial clock), SDA (serial data), RES (reset), DC (or D/C: data/command) and BLK (back light).
Connecting the BLK pin is optional. The back light turns off when the BLK pin connected to the ground (GND).