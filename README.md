<h1 align="center"> macOS on Lenovo Thinkpad E570 </h1>

<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/ThinkPad%20E570.png" alt="Thinkpad E570" width="500">
</p>

<h4 align="center"> OpenCore config for Hackintosh Lenovo Thinkpad E570 </h4>

<p align="center">
<a href="https://www.apple.com/macos/monterey/">
  <img src="https://img.shields.io/badge/macOS-Monterey_v12.3-blue"/> </a>
<a href="https://github.com/acidanthera/OpenCorePkg">
  <img src="https://img.shields.io/badge/OpenCore-0.7.9-9cf"/> </a>
<a href="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/releases">
  <img src="https://img.shields.io/badge/release-EFI-blue.svg"/> </a>
</p>
<p align="center">
<a href="https://t.me/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-2CA5E0?style=flat-square&logo=Telegram&logoColor=blue"/> </a>
<a href="https://www.youtube.com/c/yusufklncc">
  <img src="https://img.shields.io/badge/-@yusufklncc-lightgrey?style=flat-square&logo=YouTube&logoColor=red"/> </a>
<a href="https://www.paypal.com/paypalme/sevenpay">
  <img src="https://img.shields.io/badge/-@sevenpay-2CA5E0?style=flat-square&logo=PayPal&logoColor=red"/> </a>

# Screenshots

<details>
<summary>Monterey</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Monterey.png">
</p>
</details>

<details>
<summary>Big Sur</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Big%20Sur.png">
</p>
</details>

<details>
<summary>Catalina</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Catalina.png">
</p>
</details>

<details>
<summary>Mojave</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Mojave.png">
</p>
</details>

<details>
<summary>High Sierra</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/High%20Sierra.png">
</p>
</details>

<details>
<summary>Sierra</summary>
<p align="center">
  <img src="https://github.com/yusufklncc/Lenovo-Thinkpad-E570-Hackintosh/blob/main/macOS%20Screenshots/Sierra.png">
</p>
</details>

# Original Hardware 💻

| **LENOVO** | Detail |
| ------------------- | - |
| Model Name      | Lenovo Thinkpad E570 | Working |
| CPU              | Intel(R) Core(TM) i5-7200U CPU @ 2.40GHz Kaby Lake | Working |
| RAM           | 8 GB 2400 MHz DDR4 | Working |
| Internal Graphics Card | Intel(R) HD Graphics 620 (1 GB) | Working |
| Wi-Fi             | Qualcomm Atheros QCA9377 | Not Working |
| Ethernet          | Realtek RTL8111 | Working |
| Audio       | Conexant CX20753/4 | Working |
  
# Modifications 🔨

| Type | Detail |
| ------------------- | ---------------------|
| Wi-Fi | Dell Wireless 1820A ac |

## Kext Used 
 
Kext | Info 
:---------|:---------
[Lilu.kext](https://github.com/acidanthera/Lilu) | An open source kernel extension bringing a platform for arbitrary kext, library, and program patching throughout the system for macOS.
[VirtualSMC.kext](https://github.com/acidanthera/VirtualSMC) | Advanced Apple SMC emulator in the kernel. Requires Lilu for full functioning.
[AppleALC.kext](https://github.com/acidanthera/AppleALC) | An open source kernel extension enabling native macOS HD audio for not officially supported codecs without any filesystem modifications.
[USBPorts.kext](https://www.youtube.com/watch?v=rlTDHkPzjAk&t=654s) | Kext to inject mapped USB Ports.
[USBInjectAl](https://github.com/Sniki/OS-X-USB-Inject-All) | Kext to inject USB ports.
[VoodooPS2Controller.kext](https://github.com/acidanthera/VoodooPS2) | Contains updated Voodoo PS/2 Controller, improved Keyboard & Synaptics TouchPad.
[WhateverGreen.kext](https://github.com/acidanthera/WhateverGreen) | Various patches necessary for certain ATI/AMD/Intel/Nvidia GPUs. This is needed for Intel HD 620.
[SMCBatteryManager.kext](https://github.com/acidanthera/VirtualSMC) | Battery Status Monitoring.
[SMCProcessor.kext](https://github.com/acidanthera/VirtualSMC) | Processor Temp Monitoring.
[SMCSuperIO.kext](https://github.com/acidanthera/VirtualSMC) | Fan Reading.
[RealtekRTL8111.kext](https://github.com/Mieze/RTL8111_driver_for_OS_X) | OS X open source driver for the Realtek RTL8111/8168 family.
[AirportBrcmFixup](https://github.com/acidanthera/AirportBrcmFixup) | An open source kernel extension providing a set of patches required for non-native Airport Broadcom Wi-Fi cards.
[BrcmPatchRAM](https://github.com/acidanthera/BrcmPatchRAM) | BrcmPatchRAM kext is a macOS driver which applies PatchRAM updates for Broadcom RAMUSB based devices.
[NVMeFix.kext](https://github.com/acidanthera/NVMeFix) | NVMeFix is a set of patches for the Apple NVMe storage driver, IONVMeFamily.
[CPUFriend.kext](https://github.com/acidanthera/CPUFriend) | A Lilu plug-in for dynamic power management data injection.
[CPUFriendDataProvider.kext](https://github.com/acidanthera/CPUFriend) | A CPUFriend plug-in for CPU power management.
[FeatureUnlock.kext](https://github.com/acidanthera/FeatureUnlock) | Lilu Kernel extension for enabling: Sidecar, NightShift, AirPlay to Mac, Universal Control.
[HibernationFixup.kext](https://github.com/acidanthera/HibernationFixup) | An open source kernel extension providing a sync between RTC variables and NVRAM.
[NoTouchID.kext](https://github.com/al3xtjames/NoTouchID) | Lilu plugin for disabling Touch ID support.
[ECEnabler.kext](https://github.com/1Revenger1/ECEnabler) | Allows reading Embedded Controller fields over 1 byte long.
  
# Update History
- ✅ macOS Monterey 12.3
- ✅ macOS Monterey 12.2.1  
- ✅ macOS Monterey 12.0.1
- ✅ macOS Big Sur 11.6.1
- ✅ macOS Big Sur 11.0.1
- ✅ macOS Catalina 10.15.7
- ✅ macOS Mojave 10.14.6
- ✅ macOS High Sierra 10.13.6
- ✅ macOS Sierra 10.12.6

# What's Working?
|                                 |                                    |
| -----------------------------------  | -------- |
|  Turbo boost and CPU frequency stage |  ✅  |
|  Intel HD Graphics 620              |  ✅  |
|  Brightness control                  |  ✅  |
|  HDMI                                |  ✅  |
|  Audio Conexant CX20753/4            |  ✅  |
|  Realtek Ethernet RTL8111            |  ✅  | 
|  DW1820A Wi-Fi and Bluetooth, Airdrop, Handoff, SideCar, iMessage...         |  ✅  |
|  USB 3.0 and Type-C (with Port Map)        |  ✅  |
|  Touchpad (14 gestures are working)   |  ✅  |
|  Battery status   |  ✅  |
|  Camera   |  ✅  |
|  S3 Sleep / Wake   |  ✅  |
|  S4 Hibernation / Wake   |  ✅  |
|  Shutdown / Reboot   |  ✅  |
|  Fn shortcut keys   |  ✅  |
 
# What You Have to Do?
|                                 |                                    |
| -----------------------------------  | -------- |
|  SMBIOS Settings  | ⚠️ |
|  Rename config    | ⚠️ |

- If you install Monterey+, you can delete BrcmBluetoothInjector.kext in OC/Kexts. 
- If you install Big Sur-, you can delete BlueToolFixup.kext in OC/Kexts.

- With OpenCore Configrator you should definitely set your SMBIOS settings because the config does not contain SMBIOS information MacBook Pro 14.1

<h1 align="center"> Donate - Bağış </h1>
<p align="center">
<a href="https://github.com/yusufklncc/yusfklncc/blob/main/Donate%20-%20Ba%C4%9F%C4%B1%C5%9F.md">
  <img src="https://github.com/yusufklncc/yusfklncc/blob/main/Resources/Donate.png" width="300">
