---
title: Katapult Configuration for the Fly-Super5Pro on CAN
tags: []
keywords: 
last_updated: 17/02/2024
summary: "How to Configure Katapult for CAN bus Operation on the Fly-Super5Pro"
sidebar: mydoc_sidebar
permalink: fly_super5_pro_katapult_can.html
folder: mydoc
comments: false
toc: true
datatable: true

boardname: Fly-Super5Pro
firmware: CANbus
mcu: "STM32"
kconfig_name: super5pro
architecture: "(STMicroelectronics STM32)"
processor: "(STM32H723)"
deployment: "(128KiB bootloader (SKR SE BX v2.0))"
clock: "(25 MHz crystal)"
communication: "(CAN bus (on PB8/PB9))"
application_offset: "(128KiB offset)"
can_bus_speed: "(1000000)"
gpio_bootloader_set: "()"
support_bootloader_entry: "[*]"
enable_bootloader_gpio: "[&nbsp;]"
enable_status: "[&nbsp;]"
board_type: "mainboard"
katapult_file: "deployer.bin"

katapult_img1: "katapult/stm32h723_can_deployer_pb8pb9.png"
katapult_cap1: "Katapult Menu Config CAN"

katapult_img2: "fly-super5_pro/fly_super5pro_sd_card.png"
katapult_cap2: "Fly-Super5Pro SD card"

katapult_img3: "fly-super5_pro/fly_super5pro_reset.png"
katapult_cap3: "Fly-Super5Pro reset button"

installKlipperURL: "./fly_super5_pro_klipper_can.html"
installKlipperName: "Klipper for CAN bus configuration section"

---

## Configuring and installing Katapult bootloader for CAN bus

{% include custom/katapult/compile.html %}

{% include custom/katapult/flash_deployer.html %}

{% include custom/mcu/super5_pro/fly_super5pro_links.html %}