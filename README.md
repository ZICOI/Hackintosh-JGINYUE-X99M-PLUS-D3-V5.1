# Hackintosh-JGINYUE-X99M-PLUS-D3-V5.1
<img width="1280" height="720" alt="Desktop" src="https://github.com/user-attachments/assets/294d621f-bd4a-4630-b7b2-bb39f38cd7d7" />



## Mainboard Photo
<img width="450" height="450" alt="IMG_1130" src="https://github.com/user-attachments/assets/9ffc01c9-db21-496d-af71-db11d0f68012" />



## Computer Specifications
| Component        | Specifications                         |
|------------------|----------------------------------------|
| Mainboard        | JGINYUE X99M-PLUS D3 V5.1 (Q87 Chipset)|
| CPU              | Intel Xeon E5-2666 v3 (2.9GHz)         |
| GPU              | AMD Radeon RX 5700XT (8GB/GIGABYTE)    |
| RAM              | SAMSUNG 32GB ECC DDR3 1866MHz (16GB*2) |
| ROM              | SAMSUNG NVMe PM9A1 1TB (Lenovo 2.9A)   |
| LAN              | Realtek RTL8111H                       |
| WiFi & Bluetooth | Intel AC9260 160MHz                    |
| Audio            | Realtek ALC897                         |
| SMBIOS           | MacPro7,1                              |
| BootLoader       | OpenCore 1.0.8                         |
| Mac OS           | Sequoia 15.8.1                         |



## BIOS Settings
| Disabled                 |  Enabled     |
|--------------------------|--------------|
| Resizable Bar            | Above 4G     |
| CSM Support (set to UEFI)| XHCI Hand-off|
| CFG Lock(MSR Lock)       | EHCI Hand-off|
| Serial Port              |              |
| Secure Boot              |              |
| Fast Boot                |              |



## Works & Not Work
| Works           | Not Work   |
|-----------------|------------|
| CPU Boost       | Sleep State|
| GPU Boost       |            |
| RAM & ROM       |            |
| WiFi & Bluetooth|            |
| USB Port        |            |
| Audio           |            |



## Attention
### To use WiFi & Bluetooth properly, you need to use [OCLP-Mod](https://github.com/laobamac/OCLP-Mod) to fix them
### [HoRNDIS](https://github.com/jwise/HoRNDIS) already comes built into the EFI-OC-kexts folder. If you’re stuck without LAN and you’re trying to restore macOS through Recovery, you can try using Android USB tethering to get your macOS online. But it’s off by default, so you’ll need to turn it on yourself in the OpenCore editor.
