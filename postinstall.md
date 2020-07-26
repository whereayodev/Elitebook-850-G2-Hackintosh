# Post installation

## Boot
After system configuration and last reboot you take acces to system

Now you must install **Clover** or **Opencore** bootloader

I'm choose **Clover** because it simple for me.

## Clover Installation
Clone **Postinstall** directory from this repo

In this folder you can find **Clover_r5120.pkg, Open it!**  
![cloverapp](https://i.imgur.com/lw825iU.jpg)  
Now, press next
![cloverapp](https://i.imgur.com/FyDvTPW.jpg)  
Choose your macOs Drive
![installation](https://i.imgur.com/QEYoRcw.jpg)  
Now, press the 'Customize button'
![type](https://i.imgur.com/ONn12pG.jpg)  
Set up checkboxes just like at screenshot and press install.
![check](https://i.imgur.com/1mLsW27.jpg)

## Clover configuration

Now, open **Clover Configurator** from Postinstall folder
![cc](https://i.imgur.com/BdnsEbD.jpg)
Go to **Mount EFI** tool
![cc2](https://i.imgur.com/hE6UY5K.jpg)
Mount and open your **EFI** Partition 
![cc3](https://i.imgur.com/SXd3vT9.jpg)
![cc4](https://i.imgur.com/ePYVZXG.jpg)
Go to Clover folder by this way:
```
/EFI/EFI/CLOVER
```  
Now, copy [Clover Files](https://github.com/nkngdev/Elitebook-850-G2-Hackintosh/tree/master/Clover%20files/CLOVER) to your clover folder with replacement
![d](https://i.imgur.com/wVWpVnT.jpg)
After this go to **Clover Configurator** and open ***config.plist***
![cc](https://i.imgur.com/MheWve4.jpghttps://i.imgur.com/MheWve4.jpg)
Next - go to SMBIOS menu and **press the button with arrows**
![2](https://i.imgur.com/d0le5se.jpg)
Choose most same config with your device ***(Screen diagonal not important)***

![22](https://i.imgur.com/kEFqXYx.jpg)  
**Now, your SMBIOS is configured**
![](https://i.imgur.com/TTA9CrZ.jpg)

## Setting up WiFi
If you buy native-support WiFi+BT Adapter (M.2) - you may skip this step.

If your WiFi adapter is Intel AC-7265 or other Intel-adapter:
1. Download **HeliPort** archive (HeliPort-itlwm-itlwmx.zip) from [Official repo](https://github.com/1hbb/OpenIntelWireless-Factory/releases)
2. Open archive
3. Move HeliPort to Applications folder
4. Pin it to dock and right click ***settings>start on login***
5. Unpin from dock if you want it
6. Press WiFi badge on bar and login to your WiFi network

## Updating kexts
Every kexts may updates during the time, updates improove stability and performance to kexts.

**To update kext:**  
1. Download Hackintool from official [repo](https://github.com/headkaze/Hackintool/releases)
2. Go to extensions tab and click ***refresh***
![44](https://i.imgur.com/fs8utXY.jpg)
3. Next, click the ***checkboxes*** on **kexts with updates**
4. Press ***Download*** button
5. After download folder opens automatically
6. Mount **EFI** using **Clover Configurator**
7. Open **EFI** folder
8. Copy updated ***kexts*** **with replacement**  
9. **Reboot**