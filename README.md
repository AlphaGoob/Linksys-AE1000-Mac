# Linksys-AE1000-Mac
MacOS kext for Linksys AE1000 WiFi USB Dongle. 

// Notes
* You can use it for macOS on you Mac or on a Hackintosh system.
* Everytime you start macOS you need to connect to your WiFi manually by repeating step 7-9
* If you don't use WiFi for about 15 minutes it will loose connection and you need to repeat the same steps

// Tested on
* macOS 10.13 High Sierra
* macOS 10.14 Mojave
* macOS 10.15 Catalina

// Step-by-step guide
1. Install the Ralink software via the DMG file
2. Put the RT2780USBWirelessDriver.Kext on your desktop
3. Open KextBeast.pkg
4. Install the kext to /System/Library/Extensions (*)
5. Install the Ralink Settings (DWA-140WirelessUtility)
6. Restart your Mac
7. Open your system preferences
8. Open the Ralink wireless settings
9. Add your Wireless Lan profile 

(*) Although it is not recommended to use the /System/Library/Extensions folder it does not seem to work if it is not in this folder. I tried both the /Library/Extensions and /EFI/CLOVER/kexts/ (Hackintosh) folders but without succes.
