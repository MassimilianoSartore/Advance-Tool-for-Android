![ata logo](https://i.postimg.cc/vTP4sccG/ata-tool.png)

	Windows ATA Tool v0.9.3.10072020
	Linux ATA Tool v0.0.2.28092020
![ata interface](https://i.postimg.cc/4XJ0rRgd/sample.png)
# 📦Download 

## Fast [Require .NET Framework 4.7.2]
[Download](https://github.com/MassimilianoSartore/Advance-Tool-for-Android-ADB-Tool/releases/download/v0.9.3.10072020W/ATA-v0.9.3.10072020-for-Windows-By-Sway.zip) Windows ATA Tool v0.9.3.10072020

   _(SHA256: 68f5b3a9a1b585cd7ef5d98d6d8c21500e59ce546680a2e570a028e5a0db08ca)_
   
[Download](https://dotnet.microsoft.com/download/dotnet-framework/thank-you/net472-web-installer) .NET Framework 4.7.2
## Slow 
[Download](https://github.com/MassimilianoSartore/Advance-Tool-for-Android-ADB-Tool/releases/download/v0.9.0.05122020W/ATA-v0.9.0.05122020-for-Windows-By-Sway.zip) Windows ATA Tool v0.9.0.05122020

   _(SHA256: 3274686bc31c213aef4ab59d4a6a7d45724cc14f0b147d7f3197d1504525ae69)_

[Download](https://github.com/MassimilianoSartore/Advance-Tool-for-Android-ADB-Tool/releases/download/v0.0.2.28092020L/ATA-v0.0.2.28092020-for-Linux-By-Sway.zip) Linux ATA Tool v0.0.2.28092020
    
## 🎁Donate
[![paypal](https://img.xda-cdn.com/t-5mJuzW3mDe18fr5PcYKckXMj4=/https%3A%2F%2Fi.postimg.cc%2Fd3rLD20q%2Fpaypal-bottom-by-sw-ay.png)](http://paypal.me/SWayGaming)
## 💡Introduction

This tool include: 
* Adb tool [30.0.5 (November 2020)](https://developer.android.com/studio/releases/platform-tools#3005_november_2020)
* Scrcpy [v1.17](https://github.com/Genymobile/scrcpy/releases/tag/v1.17) 

This tool currently only supports Windows and Linux, in future updates I might add support for macOS.

## ✨ Windows Features: 
* UNLOCK BOOTLOADER 
* LOCK BOOTLOADER 
* FORMAT DATA PARTITION (EXT4) 
* FORMAT DATA PARTITION (F2FS)  
* FLASH BOOT (only .img file)
* FLASH BOOTLOADER (only .img file)
* FLASH RADIO (only .img file)
* FLASH RECOVERY (only .img file)
* FLASH SYSTEM (only .img file)
* FLASH VENDOR (only .img file)
* FLASH CACHE (only .img file)
* FLASH ROM (You must know what you are doing)
* Check connected devices 
* Boot into ROM 
* Boot into recovery 
* REBOOT SMARTPHONE  
* REBOOT INTO THE RECOVERY 
* REBOOT INTO THE Fastboot/Bootloader 
* Check connected devices 
* Check devices version
* Install an app 
* Unistall an app  
* Emulate device (Resize Screen) 
* Emulate device (Change Density) 
* Reset (Emulate device)  
* Screen Recording
* Smartphone Status
* Change system info
* Grant WRITE_SECURE_SETTINGS permission
* Grant DUMP permission
* Check for granted permissions
* Enable/Disable Dark Mode in Q
* Factory reset
* Device ID
* Sideload a zip
* Logcat and Display On Screen Only
* Logcat and Record Text File Locally
* "getevent" and Display On Screen Only
* "getevent" and Record Text File Locally
* View System Info (Data From build.prop, g.prop, and others), [External script view_buildprop_info.bat]
* adb backup and restore

* **Scrcpy** - Screen mirror
* **ADB over network** working
* Create and run a program

    keyevent Istruction 
    https://developer.android.com/reference/android/view/KeyEvent.html
    
## ✨ Linux Features: 
* Check connected devices
* REBOOT SMARTPHONE
* REBOOT INTO THE RECOVERY 
* REBOOT INTO THE Fastboot/Bootloader 
* Check devices version
* Enable/Disable Dark Mode in Q
* Device serial number
* Sideload a zip
* FORMAT DATA PARTITION (EXT4) 
* FORMAT DATA PARTITION (F2FS)  
* FLASH RECOVERY (only .img file) 
* FLASH KERNEL (only .img file) 
* FLASH ROM (You must know what you are doing) 
* Hard Reset
* List of non system app
* List of system app
* Install an app
* Unistall an app (No System App/System App)

## 🌞Windows Requirements 

1.	To run Scrcpy the Android device requires at least API 21 (Android 5.0).

2.	Make sure you [enabled adb debugging](https://developer.android.com/studio/command-line/adb.html#Enabling) on your device(s).
	On some devices, you also need to enable [an additional option](https://github.com/Genymobile/scrcpy/issues/70#issuecomment-373286323)

## 🐧Linux Requirements 


1.	To run Scrcpy the Android device requires at least API 21 (Android 5.0).

2.	Make sure you [enabled adb debugging](https://developer.android.com/studio/command-line/adb.html#Enabling) on your device(s).
	On some devices, you also need to enable [an additional option](https://github.com/Genymobile/scrcpy/issues/70#issuecomment-373286323)

3.	How to Install Scrcpy https://github.com/Genymobile/scrcpy#linux

## ATA Licence

    Copyright (C) 2019-2021 SwayWasTaken

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    
## ❓What is Scrcpy?

[Scrcpy](https://github.com/Genymobile/scrcpy) was created by the team behind the popular Android emulator Genymotion, but it is not an Android emulator itself, it displays and controls Android devices connected via USB or TCP/IP, it does not require any root access.

Scrcpy works by running a server on your Android device, and the desktop application communicates using USB (or using ADB tunneling wireless). The server streams the H.264 video of the device screen. The client decodes the video frames and displays them. The client captures input (keyboard and mouse) events, sends them to the server, and the server injects them into the device. [The documentation](https://github.com/Genymobile/scrcpy/blob/master/DEVELOP.md) provides more details.

If you want to see your Android screen interact with the app or content on your desktop, record your phone screen or perform other basic tasks, then Scrcpy is a good choice.

In short, Scrcpy is an excellent way to easily view your Android screen on your computer and interact with it in real time.

## Scrcpy Licence

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
          
    Copyright (C) 2018 Genymobile
    Copyright (C) 2018-2021 Romain Vimont


## ❓What is SDK Platform Tools?

[Android™ SDK Platform-Tools](https://developer.android.com/studio/releases/platform-tools.html) is a component for the Android™ SDK. It includes tools that interface with the Android platform, such as adb, fastboot, and systrace. These tools are required for Android app development. They're also needed if you want to unlock your device bootloader and flash it with a new system image.

Although some new features in these tools are available only for recent versions of Android, the tools are backward compatible, so you need only one version of the SDK Platform-Tools.

## SDK Platform Tools Licence

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    
    Android is a trademark of Google LLC.

    Copyright (C) 2016-2019 Google LLC	https://developer.android.com/license
