# Elitebook-850-G2-Hackintosh
Installing and using MacOs Catalina on HP Elitebook 850 G2 (Broadwell)

![Screen1](https://i.imgur.com/5MixI3H.jpg)

Hi there!
I got tired of using Windows for my work, and I decided to install the hackintosh.

My laptop is **HP Elitebook 850 G2** (I5 5300U, HD Graphics 5500, 8GB RAM, 180GB Intel Pro SSD)

# Мануал на русском

Скоро.

# Works
- **Almost all**
- BT **(Low range)**
- WIFI **(50/50)**
- LTE **(Not checked, but it seems in system)**
- Camera, Mic
- Siri
- VGA Output
- DisplayPort ***(Not tested)***
- Touchpad & Keyboard
- USB 3.0
- Brightness
- Hardware buttons **(Mute sound, airplane mode)**
- Sound **(Native Apple ALC)**
- Shortcuts **(fn+f1-f10)**
- Intel **QuickSync**

# Current Issues

- **Sleep mode (Need's DSDT patching, who knows how ti fix it - write me)**
- WIFI **(works with [iltwm](https://github.com/OpenIntelWireless/itlwm) and [heliport](https://github.com/OpenIntelWireless/HeliPort))**
- Airdrop\Handoff\Countiniuty ***(All works, like native, with BCM94352Z)***
- FaceTime, iMessage ***(I'm so lazy to find work's S\N, but it's possible)***

# Installation

**Installation is easy, liitle-more harder than Windows install**
[Installation tutorial](https://github.com/nkngdev/Elitebook-850-G2-Hackintosh/blob/master/Installation.md)

# Post-installation

[Post-installation tutorial](https://github.com/nkngdev/Elitebook-850-G2-Hackintosh/blob/master/postinstall.md)

# Downloads

**[OSX images for BDU](https://github.com/nkngdev/Elitebook-850-G2-Hackintosh/blob/master/OSX%20Images/%5Bmac-ru.net%5D.t1402.torrent)**

# Kexts

- AppleALC
- CPUFriend
- EnableLidWake 
- FakePCIID
- GenericUSBXHCI
- HibernationFixup
- IntelBluetoothFirmware
- IntelBluetoothInjector
- IntelMausi
- IOath3kfrmwr
- IOBluetoothFamily
- itlwm
- LegacyLT4112
- Lilu
- RealtekRTL8111
- SATA-Unsupported
- SMCBatteryManager
- SMCLightSensor
- SMCProcessor
- SMCSuperIO
- USBInjectAll
- VirtualSMC
- VodooI2C
- VodooI2CSynaptics
- VodooInput
- VodooPS2Controller
- WhateverGreen
- XHCI-unsupported


# DSDT

[My dsdt (not perfect)](https://github.com/nkngdev/Elitebook-850-G2-Hackintosh/tree/master/Clover%20files/CLOVER/ACPI)

# Write me if you know how to fix sleep
[My telegram](httpsL//t.me/nkngnkng)

