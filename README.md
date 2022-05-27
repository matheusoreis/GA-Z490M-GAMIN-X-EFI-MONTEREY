# Gigabyte Z490M GAMIN X EFI MONTEREY - iGPU
 
**Latest working macOS**: 12.4
<br>
**Current OpenCore**: 0.8.0

## Complete hardware specs
- Intel i5 10400 @ Stock
- Gigabyte Z490M Gaming X
- iGPU UHD 630
- 16Gb DDR4

## What works
- macOS macOS Monterey
- Audio
- HDMI/DP
- All USB ports
- Wifi and Bluetooth (Fenvi Ax3000 rgb) (AirportItlwm-MONTEREY.kext, BlueToolFixup.kext, FeatureUnlock.kext, IntelBluetoothFirmware.kext)
- Shutdown/Reboot/Update to newer macOS builds over time

## What doesn't work
- HDMI AUDIO - UNTESTED!

## Kexts used:
- AirportItlwm-MONTEREY.kext
- AppleALC.kext
- BlueToolFixup.kext
- FeatureUnlock.kext
- IntelBluetoothFirmware.kext
- IntelMausi.kext
- Lilu.kext
- NVMeFix.kext
- SMCProcessor.kext
- SMCSuperIO.kext
- USBInjectAll.kext - DEACTIVATED
- USBMap.kext
- VirtualSMC.kext
- WhateverGreen.kext

## USB Map:
![image](https://user-images.githubusercontent.com/47448206/170695080-911bf811-abfc-4f1f-a15c-e2357e8270b5.png)

## Geekbench Results:
- N/A :(

## Thanks/Credits
- [Opencore Team](https://dortania.github.io/getting-started/)
- [AF Aguiar](https://www.facebook.com/A13F2/)
