# [MSI-MAG-B760M-MORTAR-WIFI-DDR4](https://www.msi.com/Motherboard/MAG-B760M-MORTAR-WIFI-DDR4) Hackintosh OpenCore EFI

### OpenCore

[OpenCore 0.9.7](https://github.com/acidanthera/OpenCorePkg)

### OS Version Tested

- macOS Sonoma 14.2.1 

### Hardware

- Motherboard: MSI-MAG-B760M-MORTAR-WIFI-DDR4
- CPU: Intel i5-13400F
- RAM: CORSAIR Dominator 4x8 DDR4 3200MHz
- SSD: MSI SPATIUM M450 1TB M2 2280 NVMe (Hackintosh)
- SSD: Kingston NV2 500GB NVMe (Windows)
- GPU: AMD Radeon™ RX 6800 XTPhantom Gaming 16GB OC
- Audio: Realtek ALC256
- Ethernet: Realtek 8125
- Wireless: Intel Wi-Fi 6E AX211 (Windows)
- Bluetooth + Wireless: BCM94360CD (Hackintosh)
- Display:LG 27QN600 27 inch + LG 24QP500 24 inch
- PSU: COOLERMASTER V850 SFX GOLD
- CASE: CASE LIAN-LI PC - O11-DYNAMIC 

### Bios Setup

##### Disable
- Fast Boot
- Secure Boot
- Serial/COM Port
- Parallel Port
- VT-d
- Compatibility Support Module (CSM)
- Thunderbolt
- Intel SGX
- Intel Platform Trust
- CFG Lock (MSR 0xE2 write protection)
##### Enable
- VT-x
- Above 4G Decoding
- Hyper-Threading
- Execute Disable Bit
- EHCI/XHCI Hand-off
- OS type: Other OS
- DVMT Pre-Allocated(iGPU Memory): 64MB hoặc cao hơn
- SATA Mode: AHCI

### Notes

- Use [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) build your SMBIOS

### ScreenShot

- Geekbench6 Score i5-13400F

![image](ScreenShot/CPU.png)

- Geekbench6 Score Metal AMD Radeon™ RX 6800 XTPhantom Gaming 16GB OC

![image](ScreenShot/Metal.png)

- Geekbench6 Score OpenCL AMD Radeon™ RX 6800 XTPhantom Gaming 16GB OC

![image](ScreenShot/OpenCL.png)