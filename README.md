# TWRP Device tree for Xiaomi Mi 9 (codenamed _"cepheus"_)

==================================
## Device specifications

| Device                  | Xiaomi Mi 9                                                         |
| ----------------------: | :-------------------------------------------------------------------|
| SoC                     | Qualcomm SM8150 Snapdragon 855 (7 nm)                               |
| CPU                     | 1x 2.84 GHz Kryo 485 & 3x 2.42 GHz Kryo 485 & 4x 1.78 GHz Kryo 485  |
| GPU                     | Adreno 640                                                          |
| Memory                  | 6GB / 8GB RAM (LPDDR4X)                                             |
| Shipped Android version | Android 9.0 upgradable to Android 11  (MIUI 12.5)                   |
| Storage                 | 64GB / 128GB / 256GB UFS 2.1 flash storage                          |
| Battery                 | Non-removable Li-Po 3300 mAh                                        |
| Dimensions              | 157.5 mm x 74.67 mm mm x 7.61 mm                                    |
| Display                 | 1080 x 2340 pixels, 19.5:9 ratio, 6.39 inches, Super AMOLED, HDR10  |
| Rear camera 1           | 48 MP, f/1.8, 27mm (wide), 1/2.0", 0.8µm, PDAF, Laser AF            |
| Rear camera 2           | 12 MP, f/2.2, 54mm (telephoto), 1/3.6", 1.0µm, PDAF, 2x optical zoom|
| Rear camera 3           | 6 MP, f/2.2, 13mm (ultrawide), 1/3.0", 1.0µm, PDAF                  |
| Front camera            | 20 MP, f/2.0, (wide), 1/3", 0.9µm                                   |
| GPS                     | GPS (L1+L5), GLONASS (L1), BDS (B1), GALILEO (E1+E5a), QZSS (L1+L5) |
| Bluetooth               | 5.0, A2DP, LE, aptX HD                                              |
| WLAN                    | Wi-Fi 802.11 a/b/g/n/ac, dual-band, Wi-Fi Direct, DLNA              |

## Features 

- Booting
- Decryption 
- ADB
- MTP
- OTG
- Vibration

## Known Issue 

1. **Format Data** option are broken, use following method instead: 
- Enter Wipe > Advanced Wipe > Select Data and Internal Storage > Swipe to Wipe

2. **Logcat produced by TWRP cannot copy to desktop**. 
- seems like txt file will have issue, need someone to verify it. 

3. **IF YOU ARE FROM NON RETROFIT, DO NOT USE THIS TWRP TO FLASH!** 
- It Won't work. spent too much time to fix this issue till lose my patience. 

4. **Pixel Experience Retrofit version isn't supported.**
- Due to different encryption method (Metadata) 

### This Recovery only supported Following Formats: 
 
 DATA - F2FS 
 CACHE - EXT4/ F2FS
 SYSTEM - EXT4/ EROFS
 VENDOR - EXT4/ EROFS


## Device picture
![Xiaomi Mi 9](https://raw.githubusercontent.com/PixelExperience/official_devices/master/images/.thumbs/300/cepheus.png)
