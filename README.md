# OpenCore Hackintosh 5600x-B550-GTX780

![photo](https://github.com/ninetails0/Hackintosh-5600x-B550/blob/main/hackintosh.png)

## System Information

| Name     |                     Model |
| :------- | ------------------------: |
| CPU      |             Ryzen 5 5600x |
| GPU      |        Nvidia GTX 780 3GB |
| SSD      |       WD SN570 500GB NVMe |
| Board    |              ASUS B550M-A |
| Ethernet |      RTL8111H Gigabit LAN |
| Audio    |  Realtek ALC887/897 CODEC |

- OpenCore: v0.7.5
- MacOS: v11.6.5 BigSur

### SMBIOS

`MacPro7,1`

Just requires changes in smbios, follow this > <https://dortania.github.io/OpenCore-Install-Guide/AMD/zen.html#platforminfo>
<https://github.com/corpnewt/GenSMBIOS> < For generating system uuid, board serials and network mac address

## What works
- Audio (`alcid=01`)
- Ethernet
- USB
- iServices
- Graphics
- Sleep

## Issues
- None yet
