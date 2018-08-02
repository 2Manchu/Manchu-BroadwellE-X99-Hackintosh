# Manchu-X99-BroadwellE-Hackintosh
Within this repository are files and links to guides I've used to create my X99 Broadwell-E Hackintosh. If you wish to distribute these files with your own creations or modifications, please link to this GitHub Repository. Feel free to adapt and use these files for your own system.

## System Specs:
- i7 6800k
- ASUS X99 STRIX GAMING
- 16GB Corsair Vengeance LPX 2666MHz DDR4
- Corsair H100i v2
- EVGA GTX 970 SSC ACX2.0
- WD Blue 500GB SSD
- EVGA 650G2 PSU

## What works:
- Graphics hardware acceleration
- Intel XCPM power management
	- Patched BIOS needed. Instructions detailed in "Extending the iMac Pro to X99" guide.
- Onboard audio
- Ethernet
- USB
	- Custom USBInjectAll.kext SSDT for ASUS X99 STRIX included. This should solve sleep issues for those with this board and Corsair AIO CPU coolers.
- Sleep/shutdown/restart

## What doesn't:
- WiFi/Bluetooth
	- I've tried many combinations of BrcmPatchRam.kext and the like, but I can't get it working. For now, I'm using HoRNDIS and an Android 8.1 phone with USB tethering for internet access. It's not a bad solution as I've set up a battery charge limiter and an auto-enabler for USB tethering.
- Sometimes boot will fail if any devices are plugged into USB3 ports, however this is not exclusive to macOS, as I've noticed this issue with Windows as well.
- iMessage/FaceTime
	- Not a big deal for me, because I don't own any Apple devices. I've heard that using a previously activated Apple ID with iMessage/FaceTime can solve this issue.

*The above sections will most likely update as I continue using my Hackintosh.*