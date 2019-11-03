shinelon-t3ti-Hackintosh
=====

2019年11月03日发现，在kext/other中放入ACPIBatteryManager.kext可解决电池电量显示问题
---
ACPIBatteryManager.kext在/Volumes/Untitled 1/EFI/CLOVER/kexts/Other/Backup目录下
---



2019年10月31日更新10.15.1的EFI文件夹，依旧没有解决电源管理和触摸板问题。
---
更新的EFI下载详见
---
https://github.com/283330601/shinelon-t3ti-Hackintosh/releases
另外，如果有跟我一样换了DW1820A的朋友，安装如果卡禁行，可以拆掉无线网卡再安装。
---
















2019年8月7日 已测试可无痛更新10.14.6

![](https://github.com/283330601/shinelon-t3ti-Hackintosh/blob/master/104908ro0ibywoyzg5yzii.jpg) 

整个EFI文件夹请见release

炫龙T3TI  9750H+1660TI 安装macOS 10.14.5 

安装包：http://bbs.pcbeta.com/viewthread-1815882-1-1.html

Clover配置文件：
https://github.com/283330601/shinelon-t3ti-Hackintosh/blob/master/config.plist

DW1820A无线网卡驱动：http://bbs.pcbeta.com/viewthread-1806949-1-1.html

处理器：9750h（核显正常识别 UHD630）

显卡：GTX 1660TI 6G（无解）

内存：16G DDR4 2666（正常识别）

主硬盘：INTEL 760P NVME 256G（已加入代码使MAC识别NVME固态硬盘）

无线网卡：博通 DW1820A（原配英特尔AC9462无解，更换DW1820A后近乎完美）

USB正常

MIC和音频正常

声音快捷键正常

摄像头正常

亮度快捷键不可用

触摸板不可用
 
