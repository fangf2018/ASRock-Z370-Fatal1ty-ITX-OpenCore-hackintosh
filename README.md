# ASRock-Z370-Fatal1ty-ITX-OpenCore-Hackintosh

## 至此z390 已经完美支持nvram 此项目于2020年2月3日停更。

[z390转移链接](https://github.com/fangf2018/ASRock-Z390-Phantom-ITX-OpenCore-Hackintosh)


## 配置

主板：华擎z370 Fatal1ty gaming-itx/ac

cpu：i7 8700k es

显卡：~~AMD rx480~~ UHD630

网卡：~~BCM943602CS~~ inter 3168


# 更新日志

### 2020-08-22
* opencore 升级0.7.2
* 添加TB3驱动含有雷电树 

### 2019-10-10
* 开启usb全端口
`HS03-HS06、HS08-HS11、HS14、SS01-SS08`
* 移除无用补丁（for z390）

### 2019-10-08
* 启动文件config优化设置 [参考](https://insanelymacdiscord.github.io/Getting-Started-With-OpenCore/)
* **加入`IOElectrify.kext`修复雷电热插拔**，


## BIOS设置

Advanced \ Chipset Configuration → Vt-d : Disabled

Advanced \ Super IO Configuration → Serial Port: Disabled

Advanced \ USB Configuration → XHCI Hand-off : Enabled

Advanced \ Chipset Configuration → Share Memory : 128MB

Advanced \ Chipset Configuration → IGPU Multi-Monitor : Enabled


# 参考
[精解OpenCore](https://blog.daliansky.net/OpenCore-BootLoader.html)

[macOS Catalina 10.15安装中常见的问题及解决方法](https://blog.daliansky.net/Common-problems-and-solutions-in-macOS-Catalina-10.15-installation.html)

[使用HIDPI解决睡眠唤醒黑屏、花屏及连接外部显示器的正确姿势](https://blog.daliansky.net/Use-HIDPI-to-solve-sleep-wake-up-black-screen,-Huaping-and-connect-the-external-monitor-the-correct-posture.html)

[OpenCore部件补丁](https://github.com/daliansky/OC-little)


# 感谢
**[daliansky](https://github.com/daliansky)（黑果小兵）**

**[RehabMan](https://bitbucket.org/RehabMan/)**

**[ZeRo° Xu](https://github.com/xzhih)(冰水加劲Q)**

**[acidanthera](https://github.com/acidanthera/OpenCorePkg)**

**[Bat.bat](https://github.com/williambj1)**
