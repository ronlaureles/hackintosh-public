# Hackintosh

## Installation

##### 1. Format USB using these settings  
Name: USB  
Format: Mac OS Extended (Journaled)  
Scheme: GUID Partition Map  

##### 2. Run this command

```bash
sudo /Applications/Install\ macOS\ High\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --applicationpath /Applications/Install\ macOS\ High\ Sierra.app --nointeraction
```

##### 3. Install Clover to USB

##### 4. Copy clover pre-installation files to USB drive EFI partition

##### 5. Install macOS

##### 6. Install Clover to OS drive

##### 7. Copy clover post-installation files to OS drive EFI partition

##### 8. Restart

##### 9. Install Realtek ALC onboard audio for Clover

##### 10. Restart

##### 11. Install Nvidia Web Drivers

Set CsrActiveConfig to 0x00 before installing Nvidia Web Driver to avoid error. After installing, set it back to 0x67.

##### 12. Done

## Clover Settings

![Clover1](clover1.png?raw=true)

![Clover2](clover2.png?raw=true)

![Clover3](clover3.png?raw=true)

## Updating OS
Uninstall Nvidia Web Driver before updating macOS
