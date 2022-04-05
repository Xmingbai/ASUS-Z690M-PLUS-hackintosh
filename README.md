===========================================================================
# ASUS-Prime-Z690M-plus-hackintosh  opencore0.8.0
更新至OC0.80，支持Catalina、big sur、Monterey12.x版本

附加AQC107 10G网卡补丁

更新kexts至最新

支持12代所有大小核心CPU型号，可同时大小核心

支持NAVI核心RX5500/5600/5700/6600/6800/6900系列显卡（vega核心系列显卡需去掉启动参数agdpmod=pikera）

重新定制15个USB端口，保留主板前置2个USB3和TYPE-C

ASUS-Z690M-PLUS-ALL21USBPorts.kext内含主板全部21个USB端口可根据机箱USB分布删除部分来定制自己所需

===========================================================================

# ASUS-Prime-Z690M-plus-hackintosh  opencore0.7.7
更新至OC0.7.7 正式版，支持Catalina、big sur、Monterey12.1版本

保持最简OC配置、更新kexts至最新

支持12代所有大小核心CPU型号，可同时开启大小核心

支持NAVI核心RX5500/5600/5700/6600/6800/6900系列显卡（vega核心系列显卡需去掉启动参数agdpmod=pikera）

重新定制15个USB端口，保留主板前置2个USB3和TYPE-C

ASUS-Z690M-PLUS-ALL21USBPorts.kext内含主板全部21个USB端口可根据机箱USB分布删除部分来定制自己所需


===========================================================================

# ASUS-Z690M-plus-hackintosh  opencore0.7.5
===========================================================================
![](https://github.com/Xmingbai/ASUS-Z690M-PLUS-hackintosh/blob/main/Monterey.png)



欢迎关注B站UP ：小明和他的女朋友

详细测评视频  https://www.bilibili.com/video/BV1Kq4y16737/

专栏文章 https://www.bilibili.com/read/cv13960802?spm_id_from=333.999.0.0 


# 1.基本硬件配置清单 及截图

PC基本硬件

CPU： i5-12600K

主板： 华硕 Prime Z690M-PLUS

内存：芝奇32G  2x16G DDR4 3600 

显卡: 公版 RX5500 4G 

硬盘：三星960 EVO（手上经常测试硬盘）

WIFI：BCM94352Z 


作者：小明和他的女朋友

# 若有其他问题请加Q群：608352460   备注小明或者B站，
 
# 也欢迎关注B站：小明和他的女朋友

此份操作指南 同步 发布于B站专栏，方便国内访问  

 https://www.bilibili.com/read/cv13960802?spm_id_from=333.999.0.0 

# 2.macOS 状况

 Catalina 10.15.x &   big sur 11.x   &  Monterey 12.1 beta
 
## PC截图

![](https://github.com/Xmingbai/ASUS-Z690M-PLUS-hackintosh/blob/main/big%20sur.png)

![](https://github.com/Xmingbai/ASUS-Z690M-PLUS-hackintosh/blob/main/Monterey.png)

![](https://github.com/Xmingbai/ASUS-Z690M-PLUS-hackintosh/blob/main/%E5%BC%80%E5%90%AF%E8%B6%85%E7%BA%BF%E7%A8%8B%2B%E5%85%B3%E9%97%AD%E5%B0%8F%E6%A0%B8%E5%BF%83.png)

## 基本功能

CPU正常睿频

显卡双硬解正常

支持显卡音频输出正常，板载音频输出正常

支持有线网卡（intel 1000M）

蓝牙、WiFi正常  支持隔空、接力

睡眠及唤醒正常，支持USB唤醒

USB 2.0 和3.0 识别正常，附件中定制不含前置USB端口


未修正的地方 ：超线程与小核心不同同时启用

# 3.bios 设置参考指南   

https://www.bilibili.com/read/cv7739198?spm_id_from=333.999.0.0


另 四大主板厂商华擎、华硕、微星、技嘉 针对性 详细截图 黑苹果bios设置 参考B站专栏


https://space.bilibili.com/591453294/article
