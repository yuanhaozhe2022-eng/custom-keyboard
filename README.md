# custom-keyboard

Hi, my name is Eric and this is my attempt on the Hack Club KEEB project.

Short description:
It's a split, 65%-style mechanical keyboard with an integrated plate, split spacebar, rotary encoder, and a small OLED display. Firmware runs on RMK.

Specs:
MCU: Raspberry Pi Pico (RP2040)
Matrix: 5 rows x 13~14 columns, wired matrix
Layout: split 65% in one case, both halves wired directly to a single Pico (no wireless link for now)
Extras: rotary encoder (volume control), 0.91" OLED (I2C)
Case: integrated plate, 3D printed in PETG (~230g), reserved space for future add-ons
Firmware: RMK, built via GitHub Actions cloud compilation
