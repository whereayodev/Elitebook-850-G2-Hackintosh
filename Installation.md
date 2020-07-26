# Installation

For installation i'm using a 16GB Flash drive.
I'm using [Clover bootoader](https://github.com/CloverHackyColor/CloverBootloader/releases)
You need 8gb drive at least to write Catalina image and Clover

## Downloading MacOs

I'm download MacOs Image usting this [.torrent file](https://github.com/nkngdev/Elitebook-850-G2-Hackintosh/blob/master/%5Bmac-ru.net%5D.t1402.torrent) 

In your torrent app chose to download:
```
✅ \torrent_root\WIN\10.15 - is a macOs image
✅ \torrent_root\EXE\  - is a BDU (BootDiskUtility)
✅ \torrent_root\FAQ\  - is a manual for BDU
```

## Writing MacOs to Flah drive

After you download MacOs in download folder you can find "BDU" app
Use [this manual](https://github.com/nkngdev/Elitebook-850-G2-Hackintosh/blob/master/BDU_FAQ_STARCOM_V2.0.pdf
) for write macOs image to your flash drive

## Edit Clover config

For sucsessful boot you need replace some files from my repo to your clover folder
Clone my files to your clover folder (Clover_partition\EFI\CLOVER\)

## BIOS Settings

**Boot options**
Startup Menu Delay - 0 sec.
Multiboot Express Popup Delay - 0 sec.

**Disable all checkboxes, except this:**

Fast boot - ✅ 
USB device boot - ✅
Pcie/M.2 SSD boot - ✅

User mode - HP Factory Keys
Boot mode - UEFI Hybrid (With CSM)

**Device Configurations**

**Disable all checkboxes, except this:**

Fn+(F1+F12) Key switch - ✅
USB legacy support - ✅
USB 3.0 (XHCI) - ✅

Video memory size:
Minimum - 128mb, i’m choose - 256

Data execution prevention - ✅

Max SATA Speed - 6.0 Gbps
**SATA Device mode - AHCI**

USB Charging port - ✅ (not important, but it’s useful)

Hybrid graphics - ❌ (not working on hackintosh)

Smart card reader power setting - Powered on if card is present

Deep sleep - ON ✅

Built-in Device Options 

Wireless button state - ✅
Embedded  WWAN device - ✅ (LTE-modem)
WWAN Quick connect - ✅
Embedded WLAN device - ✅ (WIFI)
Embedded Bluetooth device - ✅
Embedded LAN controller - ✅

Integrated Camera - ✅ 
Audio device - ✅
Microphone - ✅
Speakers and headphones - ✅
PciE/M.2 SSD - ✅

**Port options**

USB Port - ✅



## Booting

1. Turn on Notebook
2. Press F10 to open Boot menu
3. Choose your Flash drive
4. In Clover choose boot option 'Install MacOs Catalina'
5. Wait for loading Setup

## Setup

1. Open Disk Utility
2. Format your Drive at APFS & GUID partition table
![img_format](https://i.imgur.com/t7FseKX.jpg)
3. Click 'Next'
4. Countiniue to installing mac os.

**Laptop may reboot a few times, after every reboot choose in clover 'Boot from your drive' NOT FLASH DRIVE!**
