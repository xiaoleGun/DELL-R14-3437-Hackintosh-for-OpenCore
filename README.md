# DELL-R14-3437-Hackintosh-for-OpenCore

## [English]()
## [简体中文]()

### 这是我维护的第一个Hackintosh的引导，它在我的设备DELL-R14-3437运行的很好，下面列出我的配置。

### CPU：i5 4200U 变频比较正常一共是5个档
### 显卡：HD4400 这个HD4400比较奇特了,我几乎没有见过它发生花屏,体质相当的好,不过有可能是因为Weg的原因造成它现在频率只有0.2Ghz，大家帮忙解决一下看看还能达到1Ghz吗。
### 声卡：ALC283(ID:88,由我(xiaoleGun)创建，由[黑果小兵(daliansky)](https://github.com/daliansky)帮忙提交ID致vit9696，现阶段耳机的Mic无法正常使用,有可能跟耳机的插孔不一样，我的是国标耳机,但是AppleALC有可能识别的是美标耳机,但是在Win和Linux下我的耳机运行正常,这个问题还是请大家研究一下吧,这个仿冒声卡我都搞了一个月了实在是筋疲力尽,所以我发布到Github等待大家的好消息。
### 网卡 & 蓝牙：Bcm94360HMB 没有屏蔽针脚但是一切正常,它是Mini Pcie接口的大家可以自己去淘宝买一个,我买的时候是150顺丰包邮。
### 触控板 & PS2键盘：自己觉得已经很正常了,触控板最多触发三个手指的操作,PS2键盘一切正常。
### 睡眠 现阶段是可以睡眠但是有一定的几率睡眠崩溃,暂时无解看看大家有没有办法。

### 电池显示 & 合盖睡眠(几率崩溃)等等一系列的问题我都已经解决了，唯一的一个问题是关机有时候不断电,这个故障是在升级到15.4发生的,各位排查一下,谢谢！

# 这个EFI必须要解锁CFG才能使用,我是使用grub命令解锁的，确保你们的BIOS升级到了A12,然后使用grub命令解锁命令如下
` ` `
//代码块
int a=0;
a++;
setup_var_3 0x95
setuo_var_3 0x95 0x00
` ` `
     
# 关于打赏
<div align=center><img width="150" height="150" src="https://github.com/xiaoleGun/DELL-R14-3437-Hackintosh-for-OpenCore/blob/master/WeChat.png"/></div>

# 这个EFI的贡献者
@[黑果小兵(daliansky)](https://github.com/daliansky)

@天成小爱

@黑果小兵微信群的所有人

@云朵有点甜

@小乐

@远景论坛上的一些大佬

@我(xiaoleGun)
