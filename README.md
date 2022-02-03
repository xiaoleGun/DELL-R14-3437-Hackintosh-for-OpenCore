# DELL-R14-3437-Hackintosh-for-OpenCore

[English](https://github.com/xiaoleGun/DELL-R14-3437-Hackintosh-for-OpenCore/blob/master/README-EN.md)

[中文](https://github.com/xiaoleGun/DELL-R14-3437-Hackintosh-for-OpenCore)

> 更新日期: 2022.02.03

> OC版本: 0.7.4

> 这是我维护的第一个Hackintosh的引导，它在我的设备DELL-R14-3437运行的很好，下面列出我的配置。

|配置|     |状态|
|---| --- | --- |
|CPU|i5 4200U|锁最高频率|
|IGPU|HD 4400|HDMI音视频正常|
|Audio|ALC283|二合一Mic不正常|
|网卡/蓝牙|BCM94360HMB|隔空、接力一切正常|

## 问题
1、可能遇到关机不断电，暂且不知道什么导致的。

2、睡眠睡死，这是普遍现象。

3、从win热重启声音可能GG，因为windows加载的audio不适用于mac。

## 解锁CFG
> 我已经于大约2020年2月24日找到了这个老爷机解锁节点，现在分享给大家。请使用Grub shell输入以下命令
``` 
setup_var_3 0x95
setuo_var_3 0x95 0x00
```
## 关于打赏
<summary>微信&支付宝</summary>

<img src="https://github.com/xiaoleGun/DELL-R14-3437-Hackintosh-for-OpenCore/blob/master/WeChat.png" width="400px"  />
<img src="https://github.com/xiaoleGun/DELL-R14-3437-Hackintosh-for-OpenCore/blob/master/Alipay.png" width="400px" />

# 贡献者
- xiaole 
<!-- 曾经喜欢的女孩子 -->
