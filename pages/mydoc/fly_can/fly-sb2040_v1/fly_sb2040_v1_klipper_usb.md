---
title: Klipper Configuration for the Fly-SB2040-V1 on USB
tags: []
keywords: 
last_updated: 15/08/2023
summary: "Klipper Configuration for the Fly-SB2040-V1 on USB"
sidebar: mydoc_sidebar
permalink: fly_sb2040_v1_klipper_usb.html
folder: mydoc
comments: false
toc: true
datatable: true
boardname: Fly-SB2040-V1
firmware: USB
mcu: "rp2040"
version: v1
kconfig_name: sb2040v1
low_level: "*"
architecture: "Raspberry Pi RP2040"
bootloader_offset: "16KiB bootloader"
communication: "USB"
usb_ids: ""
gpio_startup: "gpio24"
board_type: "toolboard"
klipper_file: "klipper.uf2"
120rurl: "./fly_sb2040_v1_120r.html"

klipper_img1: "klipper/rp2040_usb_gpio24.png"
klipper_cap1: "Klipper Menu Config USB"

klipper_img2: "fly-super8/fly-super8_klipper_makeflash_burn.png"
klipper_cap2: "Burn Klipper firmware over USB"

---
{% include important.html content="This guide assumes you have a working Klipper host installation on a Raspberry Pi or compatible device" %}

{% include custom/klipper/menuconfig.html %}

{% include custom/klipper/flash_canboot_usb.html %}

{% include custom/mcu/sb2040v1/sb2040_v1_links.html %}