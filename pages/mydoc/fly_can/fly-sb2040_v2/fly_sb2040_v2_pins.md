---
title: Fly-SB2040-V2 Pin Definitions
tags: []
keywords: 
last_updated: 23/07/2023
summary: "Fly-SB2040-V2 pin map"
sidebar: mydoc_sidebar
permalink: fly_sb2040_v2_pins.html
folder: mydoc
comments: false
toc: true
datatable: true

mcu: "Fly-SB2040-V2"

sb2040pins_img1:  "fly_sb2040_v2/pinout.jpg"
sb2040pins_cap1:  "Fly-SB2040-V2 pin locations" 

sb2040pins_img2:  "fly-sb2040_v1/fly-sb2040_fan_pins.jpg"
sb2040pins_cap2:  "Fly-SB2040-V2 Fan board pin locations" 

sb2040pins_img3:  "fly-sb2040_v1/sb2040_xt30.png"
sb2040pins_cap3:  "Fly-SB2040-V2 XT30 2+2" 

sb2040pins_img4:  "fly-sb2040_v1/sb2040_extruder.png"
sb2040pins_cap4:  "Fly-SB2040-V2 Extruder" 

sb2040pins_img5:  "fly-sb2040_v1/sb2040_hotend.png"
sb2040pins_cap5:  "Fly-SB2040-V2 Hot End" 

sb2040pins_img6:  "fly-sb2040_v1/sb2040_induction.png"
sb2040pins_cap6:  "Fly-SB2040-V2 Induction Probe" 

sb2040pins_img7:  "fly-sb2040_v1/sb2040_klicky.png"
sb2040pins_cap7:  "Fly-SB2040-V2 KLicky Probe" 

sb2040pins_img8:  "fly-sb2040_v1/sb2040_bltouch.png"
sb2040pins_cap8:  "Fly-SB2040-V2 BLTouch" 

sb2040pins_img9:  "fly-sb2040_v1/sb2040_tap.png"
sb2040pins_cap9:  "Fly-SB2040-V2 Voron Tap" 

sb2040pins_img10:  "fly-sb2040_v1/sb2040_limit.png"
sb2040pins_cap10:  "Fly-SB2040-V2 Limit Switches" 

sb2040pins_img11:  "fly-sb2040_v1/sb2040_analog_fans.png"
sb2040pins_cap11:  "Fly-SB2040-V2 Fans" 

sb2040pins_img12:  "fly-sb2040_v1/sb2040_pwm.png"
sb2040pins_cap12:  "Fly-SB2040-V2 PWM Fans" 

sb2040pins_img13:  "fly-sb2040_v1/sb2040_rgb.png"
sb2040pins_cap13:  "Fly-SB2040-V2 RGB LED" 

sb2040_cfg: "./files/fly_sb2040_v2/fly_sb2040_v2.cfg"
---


    {% capture sb2040pins_img1 %}{{page.sb2040pins_img1 }}{% endcapture %}
    {% capture sb2040pins_cap1 %}{{page.sb2040pins_cap1 }}{% endcapture %}
    {% capture sb2040pins_url1 %} .\images\{{ page.sb2040pins_img1 }} {% endcapture %}

    {% capture sb2040pins_img2 %}{{page.sb2040pins_img2 }}{% endcapture %}
    {% capture sb2040pins_cap2 %}{{page.sb2040pins_cap2 }}{% endcapture %}
    {% capture sb2040pins_url2 %} .\images\{{ page.sb2040pins_img2 }} {% endcapture %}

    {% capture sb2040pins_img3 %}{{page.sb2040pins_img3 }}{% endcapture %}
    {% capture sb2040pins_cap3 %}{{page.sb2040pins_cap3 }}{% endcapture %}
    {% capture sb2040pins_url3 %} .\images\{{ page.sb2040pins_img3 }} {% endcapture %}

    {% capture sb2040pins_img4 %}{{page.sb2040pins_img4 }}{% endcapture %}
    {% capture sb2040pins_cap4 %}{{page.sb2040pins_cap4 }}{% endcapture %}
    {% capture sb2040pins_url4 %} .\images\{{ page.sb2040pins_img4 }} {% endcapture %}

    {% capture sb2040pins_img5 %}{{page.sb2040pins_img5 }}{% endcapture %}
    {% capture sb2040pins_cap5 %}{{page.sb2040pins_cap5 }}{% endcapture %}
    {% capture sb2040pins_url5 %} .\images\{{ page.sb2040pins_img5 }} {% endcapture %}

    {% capture sb2040pins_img6 %}{{page.sb2040pins_img6 }}{% endcapture %}
    {% capture sb2040pins_cap6 %}{{page.sb2040pins_cap6 }}{% endcapture %}
    {% capture sb2040pins_url6 %} .\images\{{ page.sb2040pins_img6 }} {% endcapture %}

    {% capture sb2040pins_img7 %}{{page.sb2040pins_img7 }}{% endcapture %}
    {% capture sb2040pins_cap7 %}{{page.sb2040pins_cap7 }}{% endcapture %}
    {% capture sb2040pins_url7 %} .\images\{{ page.sb2040pins_img7 }} {% endcapture %}

    {% capture sb2040pins_img8 %}{{page.sb2040pins_img8 }}{% endcapture %}
    {% capture sb2040pins_cap8 %}{{page.sb2040pins_cap8 }}{% endcapture %}
    {% capture sb2040pins_url8 %} .\images\{{ page.sb2040pins_img8 }} {% endcapture %}

    {% capture sb2040pins_img9 %}{{page.sb2040pins_img9 }}{% endcapture %}
    {% capture sb2040pins_cap9 %}{{page.sb2040pins_cap9 }}{% endcapture %}
    {% capture sb2040pins_url9 %} .\images\{{ page.sb2040pins_img9 }} {% endcapture %}

    {% capture sb2040pins_img10 %}{{page.sb2040pins_img10 }}{% endcapture %}
    {% capture sb2040pins_cap10 %}{{page.sb2040pins_cap10 }}{% endcapture %}
    {% capture sb2040pins_url10 %} .\images\{{ page.sb2040pins_img10 }} {% endcapture %}

    {% capture sb2040pins_img11 %}{{page.sb2040pins_img11 }}{% endcapture %}
    {% capture sb2040pins_cap11 %}{{page.sb2040pins_cap11 }}{% endcapture %}
    {% capture sb2040pins_url11 %} .\images\{{ page.sb2040pins_img11 }} {% endcapture %}

    {% capture sb2040pins_img12 %}{{page.sb2040pins_img12 }}{% endcapture %}
    {% capture sb2040pins_cap12 %}{{page.sb2040pins_cap12 }}{% endcapture %}
    {% capture sb2040pins_url12 %} .\images\{{ page.sb2040pins_img12 }} {% endcapture %}

    {% capture sb2040pins_img13 %}{{page.sb2040pins_img13 }}{% endcapture %}
    {% capture sb2040pins_cap13 %}{{page.sb2040pins_cap13 }}{% endcapture %}
    {% capture sb2040pins_url13 %} .\images\{{ page.sb2040pins_img13 }} {% endcapture %}

## {{page.summary}}

{% include image.html file=sb2040pins_img1 url=sb2040pins_url1 alt=sb2040pins_cap1 caption=sb2040pins_cap1 %}

### Table of pin functions

<div class="datatable-begin"></div>

| **Device** |  **Function** | **Pin number** | **Alias** |
|:-----------|:--------------|:---------------|:----------|
|**CAN BUS** |CAN-RX| **gpio4**  | |
|**CAN BUS** |CAN-TX| **gpio5**  | |
|**Extruder** |EN| **gpio7** |EXT_EN |
|**Extruder** |STEP| **gpio9**  | EXT_STEP |
|**Extruder** |DIR| **gpio10**  | EXT_DIR |
|**Extruder** |UART| **gpio8**  | EXT_UART |
|**Endstop** |0| **gpio28** | LIMIT_0|
|**Endstop** |1| **gpio29** | LIMIT_1|
|**Endstop** |HV 2| **gpio25** | LIMIT_2|
|**Hotend**  |Heater| **gpio6** | HE0 |
|**Hotend**  |Tempreture | **gpio27** | TH0 |
|**Chamber** |Tempreture | **gpio26** | TH1 |
|**Fans** |Fan 0| **gpio13** | FAN0 |
|**Fans** |Fan 1| **gpio14** | FAN1 |
|**Fans** |Fan 2| **gpio15** | FAN2 |
|**SPI** |CLK | **gpio0** | |
|**SPI** |MISO | **gpio2** | |
|**SPI** |MOSI | **gpio3** | |
|**SPI** |ADXL-CS | **gpio1** | ADXL |
|**SPI** |ADXL-INT1 | **gpio21** |  |
|**SPI** |ADXL-INT2 | **gpio20** |  |
|**LED** |RGB LED | **gpio12** | RGBLED |
|**LED** |Status LED| **gpio25** | |

<div class="datatable-end"></div>

### Sample Configuration file: [{{page.mcu}}.cfg]({{page.sb2040_cfg}})

### CANbus Termination Resistor

CANbus bus protocol there must be only two 120 ohm resistors on a bus.  
No matter how many USB devices you connect, as long as it is on the same bus only two 120-ohm resistors are to be configured. These resistors should be at either ends of the bus.  
After connecting CAN H and CAN L signal lines, use a multimeter to measure between CAN H and CAN L. The resistance between the two should be 60 ohms.  

{% include image.html file="fly_sb2040_v2/120_ohm_resistor.png" url="./images/fly_sb2040_v2/120_ohm_resistor.png" alt="Fly-SB2040-V2 120 Ohm Resistor" caption="Fly-SB2040-V2 120 Ohm Resistor" %}

### XT30 2+2 Wiring

<div class="datatable-begin"></div>

| **Color* |  **Function** |
|:-----------|:--------------|
|**RED** | 12/24V|
|**BLACK** | GND|
|**YELLOW**| CAN H |
|**WHITE**| CAN L |

<div class="datatable-end"></div>

{% include image.html file=sb2040pins_img3 url=sb2040pins_url3 alt=sb2040pins_cap3 caption=sb2040pins_cap3 %}

### Extruder Wiring

{% include image.html file=sb2040pins_img4 url=sb2040pins_url4 alt=sb2040pins_cap4 caption=sb2040pins_cap4 %}

### Hotend Wiring

- The heating circuit supports a maximum current of 10A

  {% include image.html file=sb2040pins_img5 url=sb2040pins_url5 alt=sb2040pins_cap5 caption=sb2040pins_cap5 %}

### Thermistor Wiring

The standard Fly-SB2040-V2 supports thermistors and PT1000. It can however be purchased with PT100 support.

{% include image.html file="fly_sb2040_v2/thermistor.png" url="./images/fly_sb2040_v2/thermistor.png" alt="Fly-SB2040-V2 Thermistor Connection" caption="Fly-SB2040-V2 Thermistor Connection" %}

If PT100 support has been purchased, there will be a chip soldered to the back of the board as identified below.  

{% include image.html file="fly_sb2040_v2/pt100_location.png" url="./images/fly_sb2040_v2/pt100_location.png" alt="Fly-SB2040-V2 PT100 Support" caption="Fly-SB2040-V2 PT100 Support" %}

If your Fly-SB2040-V2 has PT100 support, connect the PT100 as shown below.  

{% include image.html file="fly_sb2040_v2/pt100.png" url="./images/fly_sb2040_v2/pt100.png" alt="Fly-SB2040-V2 PT100 Install" caption="Fly-SB2040-V2 PT100 Install" %}

### Z Probe Wiring

#### Induction Probe

- The official recommendation of VORON is to use the Omron Omron TL-Q5MC

  {% include image.html file=sb2040pins_img6 url=sb2040pins_url6 alt=sb2040pins_cap6 caption=sb2040pins_cap6 %}

#### Klicky Probe

- Klicky is a third-party leveling sensor that can be made at home at a very low cost, and its performance is stable and cost-effective. The wiring method is shown in the figure below.

  {% include image.html file=sb2040pins_img7 url=sb2040pins_url7 alt=sb2040pins_cap7 caption=sb2040pins_cap7 %}

#### BL Touch

- BL-touch has a total of five wires, three for the first group, responsible for the power supply of the sensor and the retraction of the probe, and the second group for the ground and signal lines, which output the limit signal. Please carefully check the wiring sequence when wiring the BL-touch, the wrong wiring may permanently damage the sensor and motherboard!!! The wiring method is shown in the figure below.

  {% include image.html file=sb2040pins_img8 url=sb2040pins_url8 alt=sb2040pins_cap8 caption=sb2040pins_cap8 %}

#### Voron Tap

- Voron Tap is the latest leveling sensor solution released by the Voron team, which has the characteristics of high precision, strong stability and good adaptability. When wiring, please pay attention to the positive and negative poles can not be reversed, otherwise it will damage the Tap sensor and even the SHT tool board.

  {% include image.html file=sb2040pins_img9 url=sb2040pins_url9 alt=sb2040pins_cap9 caption=sb2040pins_cap9 %}

### Limit switches

- There are two types of limit switches: normally open (NO) and normally closed (NC). Generally, on 3D printers, it is recommended to use normally closed (NC), so that when there is a problem with the limit switch line, the system will report an error in time, which can avoid some unnecessary crashes and avoid damage to the printer.

  {% include image.html file=sb2040pins_img10 url=sb2040pins_url10 alt=sb2040pins_cap10 caption=sb2040pins_cap10 %}

### Fan Board Pins

  {% include image.html file=sb2040pins_img2 url=sb2040pins_url2 alt=sb2040pins_cap2 caption=sb2040pins_cap2 %}

<div class="datatable-begin"></div>

| **Device** |  **Function** | **Pin number** | **Label at header** | **Label at Pad** |**Alias**|
|:-----------|:--------------|:---------------|:----------|:----------|
|**Fans** |Fan 0| **gpio13** | PCF | **AGND(Part Fan)** | FAN0 |
|**Fans** |Fan 1| **gpio14** | HEF | **AGND(Hot End Fan)** | FAN1 |
|**Fan PWM**| Fan 0 PWM | **gpio17** | A1 | **PWM1** | |
|**Fan PWM**| Fan 1 PWM | **gpio16** | A2 | **PWM0** | |
|**LED** |RGB LED | **gpio12** | LED   | **S** | RGBLED |

<div class="datatable-end"></div>  

- SB2040 supports up to two controllable fans, fan voltage can be selected 24V, 5V, support 2, 3, 4-wire fans, wiring method is as follows.

  {% include image.html file=sb2040pins_img11 url=sb2040pins_url11 alt=sb2040pins_cap11 caption=sb2040pins_cap11 %}

  {% include image.html file=sb2040pins_img12 url=sb2040pins_url12 alt=sb2040pins_cap12 caption=sb2040pins_cap12 %}

### RGB Wiring

- The positive and negative poles of the RGB LEDs must not be reversed, otherwise it will damage the CAN tool board.

  {% include image.html file=sb2040pins_img13 url=sb2040pins_url13 alt=sb2040pins_cap13 caption=sb2040pins_cap13 %}

{% include custom/mcu/sb2040v2/sb2040_v2_links.html %}