# ASUS X556UQK - OpenCore Files
##  Important Information - DEVICE DETAILS
|Title|Info|
|-|-|
|Model|X556UQK|
|BIOS Version|318|
|CPU|Intel Core I5 7200U (Kaby Lake - U)|
|Graphics|Intel HD Graphics 620 + NVIDIA GTX 940MX (Disabled)|
|Wi-Fi|QCNFA335 (AR9565)|
|Ehternet|Realtek RTL8168/8111|
|Audio|Realtek ALC255|
## Important Information - FIRSTLY README PLEASE
- DSDT.AML extract from BIOS Version of 318. If you use another bios version, maybe this EFI file not work correctly.
- For a better Hackintosh Experience you should change Wi-Fi Card. Because Bluetooth is not working correctly. If you can fix it, you can report it as an issue.
- DSDT Patch important for ASUS FN Keys. Please don't delete in config.plist.
- If you use this EFI, please don't forget change SMBIOS details. (It's Dummy SMBIOS Inside. Pay particular attention to this, SMBIOS MacBookPro14,2 (Because HDMI Port Problems))
- CPU Power Management is complete with CPUFriendFriend.
## Important Information - BROKEN DEVICES
- NVIDIA GTX 940MX (Disabled for Battery Drain)
- Bluetooth Device (Can't find devices)
- SDCard Slot (Not tested. Most probably not working)
- All other devices are working. Tested and Passed :)
## DSDT Patches
- RehabMan Laptop Repo
	- Fix PARSEOP_ZERO Error (aggressive)
- AsusSMC Repo
	- All Fn Keys Patch
