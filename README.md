# IOT - RGB LED Matrix 32x16

<picture>
  <img alt="image 1" src="/images/img_2.png">
</picture>

# Overview

The purpose of this project is to create a LED pannel IOT to display text and low resolution images. 

tools used :
- 3D printer
- soldering iron
- screwdriver


components used :

- P6 LED pannel - DFR4071 [documentation link](https://wiki.dfrobot.com/32x16_RGB_LED_Matrix_-_6mm_pitch_SKU_DFR0471)
- Node MCU ESP8266 
- custom PCB
- female DC Connectors
- Male + Female socket row strip
- 8x2 IDC connector wire female to female
- 5 dupont wire female to female
- heat Shrink Tubing
- PLA for 3D printer
- wires
- screws

files available on this repository :

- Gerber file of the PCB custom
- 3D parts 

# 

I used [Pxmatrix library](https://github.com/2dom/PxMatrix) to control the LED pannel, therefore, I didn't need to use any LED driver, I simply linked all to the ESP8266.

<picture>
  <img alt="image 1" src="/images/img_1.jpg">
</picture>

