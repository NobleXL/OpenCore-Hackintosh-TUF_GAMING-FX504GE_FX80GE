# OpenCore-Hackintosh-TUF_GAMING-FX504GE_FX80GE

**MacOS版本：10.15.7**

**OpenCore版本：0.7.4**

## 电脑配置

|   配件   |                      规格                      | 工作状态 |
| :------: | :--------------------------------------------: | :------: |
|   模组   |                    FX504GE                     |    ✅     |
|  处理器  |         Intel Core i5-8300H @ 2.30Ghz          |    ✅     |
|   内存   |               8+8GB DDR4 2666Mhz               |    ✅     |
| 固态硬盘 |            Samsung SSD 860 QVO 1TB             |    ✅     |
| 固态硬盘 |      KINGSTON RBUSNS8154P3128GJ  (119 GB)      |    ✅     |
| 核芯显卡 |             Intel UHD Graphics 630             |    ✅     |
| 独立显卡 |           NVIDIA GeForce GTX 1050 4G           |    🚫     |
|   声卡   |                 Realtek ALC255                 |    ✅     |
| 有线网卡 |       Realtek PCIe GbE Family Controller       |    ✅     |
| 无线网卡 | Realtek 8821CE Wireless LAN 802.11ac PCI-E NIC |    ✅     |

## 工作的部分

- MacOS 10.15.7
- CPU（睿频4.0Ghz）
- 核芯显卡
- 有线网卡
- 音频（Layout=31）
- USB（定制USBPorts.kext）
- 触摸板
- 摄像头
- 蓝牙（带有蓝牙开关）
- Wi-Fi（使用 COMGAST))

## 不工作的部分

- 独立显卡
- HDMI

## PS

- VoodooPS2Controller.kext 升级后会导致内置键盘无法使用
- 冷启动才可以使用内置扬声器