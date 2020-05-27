# TWRP Device Tree For Infinix Smart 3 Plus (X627) 32+2

## About Device

![Infinix Smart 3 Plus](https://fdn2.gsmarena.com/vv/pics/infinix/infinix-smart3-plus-1.jpg)

### Specifications

Component Type | Details
-------:|:-------------------------
CPU     | Octa-core 2.0 GHz Cortex-A53 Helio A22
Platform | MediaTek MT6761
GPU     | PowerVR GE8320
Architecture | 32 bit
Memory  | 2 GB RAM
Shipped Android Version | 	Android 9.0 Pie
Storage | 32 GB F2FS (expandable storage up to 256GB (VFAT))
Battery | 3500 mAh
Height | 157 mm
Width | 76 mm
Thickness | 7.8 mm
Weight | 148 g
Display | 6.21" (96.3 cm2)
Screen resolution | 720 x 1520 pixels
Pixel density | 271 PPI
Video | 1080p, 720p video, 30fps
Primary Camera | 13 MP + 8 MP + 2 MP Triple Rear Camera, PDAF
Secondary Camera | 8 MP, f/2.0, 1.6µm
Quick charging | No
Wifi | Yes, IEEE802.11 a/b/g/n, Supports 5G Wi-Fi Signal / Wi-Fi Direct / Wi-Fi Display
Bluetooth | v5.0, Bluetooth HID, A2DP, LE
Micro USB | Yes
NFC | No
Network support | Both SIM slots are compatible with 4G, support 4G VoLTE in both slots simultaneously
GPRS | Available
EDGE | Available
SIM size | SIM1: Nano, SIM2: Nano
CARD slot |	microSD, up to 128 GB (dedicated slot)
Sensors | Fingerprint (rear-mounted), Accelerometer, Gyroscope, Geomagnetic Sensor

Network | Bands
-------:|:-------------------------
2G | GSM 850 / 900 / 1800 / 1900 - SIM 1 & SIM 2
3G | HSDPA 850 / 900 / 2100
4G | LTE band 1(2100), 3(1800), 5(850), 8(900), 38(2600), 40(2300), 41(2500)
Speed | HSPA 42.2/5.76 Mbps, LTE Cat4 150/50 Mbps

**This device tree can be used to build TWRP for Infinix Smart 3 Plus (X627) 32+2**


## Build Instructions
```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch omni_X627-eng
mka recoveryimage
```
