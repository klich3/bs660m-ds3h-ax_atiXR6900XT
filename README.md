# Hackintosh GIGABYTE B660M DS3H AX DDR4 - i7-12700F

This repository contains the files needed to set up a Hackintosh with the ***GIGABYTE B660M DS3H AX DDR4*** motherboard and Intel ***i7-12700F*** processor. Here you will find everything you need to create a working system with the following features:

Mother board official site: https://www.gigabyte.com/Motherboard/B660M-DS3H-AX-DDR4-rev-1x#kf

* Supports 13th/12th Gen Intel® Core™ Series Processors
* Dual Channel Non-ECC Unbuffered DDR4, 4 DIMMs  
* 6+2+1 Phases Hybrid Digital VRM with MOS Heatsink 
* WIFI 6 802.11ax 2T2R & BT5 with AERO Antenna 
* Fast 2.5 GbE LAN with Bandwidth Management  
* Dual Ultra-Fast NVMe PCIe 4.0 x4 M.2 with Thermal Guard  
* Rear SuperSpeed USB 3.2 Gen 2 TYPE-C® for Fast and Versatile Connections   
* High Quality Audio Capacitors and Audio Noise Guard 
* RGB FUSION 2.0 supports Addressable LED & RGB LED Strips  
* Smart Fan 6 Features Multiple Temperature Sensors , Hybrid Fan Headers with FAN STOP  
* Q-Flash Plus Update BIOS without Installing the CPU, Memory and Graphics Card  


![MotherBoard](Images/500-2.png)
![MotherBoard Ports](Images/500-1.png)

***OpenCore: 0.9.6 - Osx Ventura - iMacPro1,1***

# Hardware

[x] Intel 12th Gen Intel(R) Core i7-12700F
    - Family: 6
    - Model: 151(86h)
    - Stepping 2
    - 2.1Ghz L3 Cache
    [x] Power Management Table

- Ram 16GB DDR4 
- M2 
[x] Hibernate / Sleep

[x] Ati Radeon XR6900XT Merc319 (is run native with out wethergreen.kext) fully supported
    [x] HDMI audio
    [x] Power Play Table
[x] PCI on m2, pci-e
[x] Ethernet RTL8125BG
[-] WiFi 6gen ax - RZ608 aka Mediatek MT7921K (BCM94360Z3)

[x] All MotherBoard USB's x7
    [x] usb-c 3.2 gen2
    [x] usb 2.0
    [x] usb 3.0
[x] Inegrated Sound Outputs


# CPU Alder Lake i7-12700F
* https://www.intel.com/content/www/us/en/products/sku/134592/intel-core-i712700f-processor-25m-cache-up-to-4-90-ghz/specifications.html
  
    Total Cores 12
    Total Threads 20

## GPU-Z

![GPU-Z](Images/cpuZ.png)

### Geekbench 6. 1.0 for Windows AVX2

* GPU Vulcan score: 148459 [Geekbench GPU Vulcan](https://browser.geekbench.com/v6/compute/1301866)
* GPU Metal score: 232433 [Geekbench GPU Metal](https://browser.geekbench.com/v6/compute/1301862)

[Geekbench CPU](https://browser.geekbench.com/v6/cpu/3586276)
* CPU Sinale-Core Score: 2354
* CPU Multi-Core Score: 7304

---

# Download 

[x] Drivers for Windows
  [x] Bluetooth / Wifi
[x] ATi Dumps
[x] Motherboard Bios
    [x] Settings with images
[x] ACPI full dump

You can ***GET*** the files needed to configure your Hackintosh from the following link [Download Hackintosh](https://ko-fi.com/s/8d36c83052).
Where is an explanation of how to configure and replicate the same hardware configuration.

Enjoy your Hackintosh with GIGABYTE B660M DS3H AX DDR4 motherboard and Intel i7-12700F processor! If you need additional help, feel free to consult the documentation and resources provided in this repository.