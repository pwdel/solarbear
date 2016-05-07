# General Guide on Setting Up USB Stick Storage for Arduino Yun (Dragino Yun)

## Introduction

Setting up storage on the Arduino Yun / Dragino Yun is different than using the SD card extended storage.  

Using the SD Card extended storage is done through a pre-programmed library called the, [SD Library](https://www.arduino.cc/en/Reference/SD), specifically by using the [ReadWrite Command](https://www.arduino.cc/en/Tutorial/ReadWrite).

In order to use a USB stick as storage, one must install a driver into the OpenWRT opearating system, and then access the USB stick through a series of commands on OpenWRT itself.
A tutorial on how to accomplish this is given on the [OpenWRT Wiki](https://wiki.openwrt.org/doc/howto/usb.storage).
