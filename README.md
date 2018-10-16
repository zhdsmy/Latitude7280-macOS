# macOS on Dell Latitude7280
This repository contains a sample configuration to run macOS (Currently Mojave Sierra 10.14) on a Dell Latitude 7280

# Hardware Configuration
* intel i5-7200u
* SK Hynix 16GB RAM
* SK hynix SC311 SATA 512GB
* 1366 * 768 resolution display 
* DW1560/BCM94352Z (replace intel wireless card)
* To be supplemented

# Current working
* display
* sound/mic (earphone supported)
* network (wired and wireless)
* bluetooth
* keyboard (include shortcuts for volume control(Fn + F1/F2/F3) and brightness control(Fn + ↑↓))
* touchpad (one finger and two finger gestures)
* usb
* hdmi/type-c(only dp tested)
* battery
* better CPU frequency conversion (rely on CPUFriend)
* webcam

# Untested or not working
* sd card
* sleep

# SSDT Hotpatch
* SSDT-RMCF.aml
* SSDT-ALC256.aml
* SSDT-ALS0.aml
* SSDT-BATT.aml
* SSDT-BRT6.aml
* SSDT-DBAT1.aml
* SSDT-DMAC.aml
* SSDT-GPRW.aml
* SSDT-HDEF.aml
* SSDT-I2C.aml
* SSDT-LPC.aml
* SSDT-MCHC.aml
* SSDT-MEM2.aml
* SSDT-PMCR.aml
* SSDT-PNLF.aml
* SSDT-PTSWAK.aml
* SSDT-SMBUS.aml
* SSDT-SMCD.aml
* SSDT-UPRW.aml
* SSDT-XHC.aml
* SSDT-XOSI.aml

# Kexts
* ACPIBatteryManager.kext
* AirportBrcmFixup.kext
* AppleALC.kext
* AppleBacklightFixup.kext
* CPUFriend.kext & CPUFriendDataProvider.kext
* FakeSMC.kext & FakeSMC_*.kext
* IntelMausiEthernet.kext
* Lilu.kext
* USBInjectAll.kext
* UVC2FaceTimeHD.kext
* VoodooI2C.kext
* VoodooI2CHID.kext
* VoodooPS2Controller.kext
* WhateverGreen.kext

# Credits
1. [the-darkvoid/XPS9360-macOS](https://github.com/the-darkvoid/XPS9360-macOS)
