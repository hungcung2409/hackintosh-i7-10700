# OpenCore Hackintosh TUF Z490

# Hardware
* [Asus TUF Z490 Plus Wifi](https://www.asus.com/vn/Motherboards-Components/Motherboards/TUF-Gaming/TUF-GAMING-Z490-PLUS-WI-FI/)

# Software
* MacOS Big Sur 11.6.1
* [OpenCorePkg - 0.6.9](https://github.com/acidanthera/OpenCorePkg/releases/tag/0.6.9)

# Kext
* AirportItlwm.kext
* AppleALC.kext
* IntelBluetoothFirmware.kext
* IntelBluetoothInjector.kext
* IntelMausi.kext
* IntelSnowMausi.kext
* Lilu.kext
* NVMeFix.kext
* SMCProcessor.kext
* SMCSuperIO.kext
* USBMap.kext
* VirtualSMC.kext
* WhateverGreen.kext


# Changelog
* 05/12/2021
  * Add new `USBMap.kext`
  * Rebuild manually [SSDT-RHUB](https://dortania.github.io/Getting-Started-With-ACPI/Universal/rhub-methods/manual.html#finding-the-acpi-path)
  * Update supported OS to Big Sur 11.6.1