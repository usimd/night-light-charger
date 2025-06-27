# Night light battery charger

One of our children's night light is battery-operated and does not feature a charging port but requires to open a battery enclosure and charge the batteries with an external charger.

This repo contains a small PCB project that adds a USB-C port for charging the three AA NiMH batteries using the [BQ25172](https://www.ti.com/lit/gpn/bq25172) charging IC. The charge current is adjustable using a potentiometer (up to the max. 800mA) and a dual color LED will indicate if the device is currently charging (red) and once charging has finished (green).

The PCB is fitted into the case of this ANSMANN device (https://shop.ansmann.de/en/cartoon-nachtlicht-maus).

## PCB design preview

This is a rendering of the board (missing a few models)

![night-light-charger](https://github.com/user-attachments/assets/ad902836-d2dd-4d80-a512-3c4e89789b06)

## Final implementation

The board fits suprisingly well into the case, I just had to remove maybe $\frac{2}{10} mm$ of the inner wall using a Dremel. Also the position of the USB-C connector is pretty well aligned with the outer wall. The dual LED intensity is strong enough to properly indicate the charging status.

Excuse my poor soldering skills, this is just to give you an impression:

<img src="https://github.com/user-attachments/assets/385b9643-3b24-4c29-9bfb-ddf059f51883" width="15%"></img> <img src="https://github.com/user-attachments/assets/cc952fc3-e7e5-4ab5-b2e9-72f8a259c800" width="15%"></img> <img src="https://github.com/user-attachments/assets/584890a5-4242-4916-8617-ddb8a6905483" width="15%"></img> <img src="https://github.com/user-attachments/assets/067b25cf-483f-48e4-88f3-1c7194757b1e" width="15%"></img> <img src="https://github.com/user-attachments/assets/d19b4f28-59f6-40a0-a1d9-12f750d532ca" width="15%"></img> <img src="https://github.com/user-attachments/assets/a1ee19fb-e466-4e0b-b12b-bc4929b7182f" width="15%"></img> 


This project has been prototyped at [AISLER](https://aisler.net/p/OOQHJCJK). 

