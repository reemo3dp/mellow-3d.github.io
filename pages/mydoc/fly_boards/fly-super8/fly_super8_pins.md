---
title: Fly-Super8 Pins
tags: []
keywords: 
last_updated: 20/10/2022
summary: "Fly-Super8 Pin map"
sidebar: mydoc_sidebar
permalink: fly_super8_pins.html
folder: mydoc
comments: false
toc: true
datatable: true

boardname: "Fly-Super8" 
ver: "V 1.2" 

---
        {% capture boardname %}{{ page.boardname }}{% endcapture %}
        {% capture ver %}{{ page.ver }}{% endcapture %}

## {{ page.boardname }} Pinout Diagram

{% 
include image.html 
file="fly-super8/fly-super8_pins.webp" 
url="images/fly-super8/fly-super8_pins.webp" 
alt="Fly-Super 8 pins" 
caption="Fly-Super8 Pinout" 
%}


{% include image.html file="fly-super8/fly_super8_pins.svg" url="images/fly-super8/fly-super8_pins.svg" alt="Fly-Super8" caption="Fly-Super8 Pinout" %}


## {{ page.boardname }} Driver Pins in Firmware

Driver pin numbers. They are separated into driver number.

<div class="datatable-begin"></div>

|Pin Type|0(X)|1(Y)|2(Z)|3(E0)|4(E1)|5(E2)|6(E3)|7(E4)|
| :------------- |:-------------|:-------------|:-------------|:-------------|:-------------|:-------------|:-------------|:-------------|
|Enable Pins|PF11|PF14|PG1|PE9|PF2|PC15|PG4|PG7|
|Step Pins|PE2|PE3|PE4|PE14|PE15|PE1|PE0|PE6|
|Direction Pins|PC5|PF13|PG0|PE8|PE11|PF0|PG3|PG6|
|UART Pins|PC4|PF12|PF15|PE7|PE10|PF1|PG2|PG5|


<div class="datatable-end"></div>

## {{ page.boardname }} Other Pins in Firmware 

If more than one pin name is availble, either name can be used in the firmware (config.g).  
If the pins aren't in the table (due to not having a special name), then the pin itself can be used in the form of PA0, PA.0, PA_0, A0, A.0 or A_0.  

<div class="datatable-begin"></div>

|Pin Number|Pin Name 1|Pin Name 2|Pin Name 3|Klipper Alias|
| :------------- |:-------------|:-------------|:-------------|:-------------|
|PA0|fan0|||FAN0|
|PA1|fan1|||FAN1|
|PA10|RX1||||
|PA15|fan4|||FAN4|
|PA2|fan2|||FAN2|
|PA3|fan3|||FAN3|
|PA4|LCD_SS|||EXP2_4|
|PA5|LCD_SCK|||EXP2_2|
|PA6|LCD_MISO|||EXP2_1|
|PA7|LCD_MOSI|||EXP2_6|
|PA8|io6||||
|PA9|TX1||||
|PB0|heat0|||HEAT0|
|PB1|heat1|||HEAT1|
|PB10|fan6|||FAN6|
|PB11|fan5|||FAN5|
|PB2|LCD_EN|||EXP1_3|
|PB3|MOT_SCK||||
|PB4|MOT_MISO||||
|PB5|MOT_MOSI||||
|PB6|BTN_EN2|||EXP2_5|
|PB7|BTN_EN1|||EXP2_3|
|PC0|ADC_4|out4||HEAT4_TEMP|
|PC1|ADC_5|out5||BED_TEMP|
|PC13|LCD_D5|||EXP1_6|
|PC14|LCD_D4|||EXP1_5|
|PC3|probe|||PROBE|
|PC6|pwm_out0|pwm0|out0|SERVO|
|PC7|heat2|||HEAT2|
|PD12|fan7|||FAN7|
|PD14|fan8|||FAN8|
|PD15|fan9|||FAN9|
|PD6|io5||||
|PD7|io4||||
|PE12|BEEP|||EXP1_1|
|PE13|BTN_ENC|||EXP1_2|
|PE5|bedout|bed||BED_OUT|
|PF3|hvin||||
|PF4|ADC_0|out0||HEAT0_TEMP|
|PF5|ADC_1|out1||HEAT1_TEMP|
|PF6|heat4|||HEAT4|
|PF7|heat3|||HEAT3|
|PF8|in7|pwm_out1|pwm1|out1|
|PF9|ADC_2|pwm_out2|pwm2|HEAT2_TEMP|
|PF10|ADC_3|out3||HEAT3_TEMP|
|PG10|io2|||E_STOP|
|PG11|io1|||Y_STOP|
|PG12|io0|||X_STOP|
|PG13|LCD_D7|||EXP1_8|
|PG14|LCD_D6|||EXP1_7|
|PG15|LCD_CD|||EXP2_7|
|PG8|LCD_RS|||EXP1_4|
|PG9|io3|||Z_STOP|
|\<GND>|GND|||EXP1_9|
|\<GND>|GND|||EXP2_9|
|\<5V>|5 VOLTS|||EXP1_10|
|\<5V>|5 VOLTS|||EXP2_10|
|\<RST>|RESET|||EXP2_8|

<div class="datatable-end"></div>




{% include custom/mcu/super8/fly_super8_links.html %}