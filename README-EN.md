# DELL-R14-3437-Hackintosh-for-OpenCore

## [English](https://github.com/xiaoleGun/DELL-R14-3437-Hackintosh-for-OpenCore/blob/master/README-EN.md)
## [简体中文](https://github.com/xiaoleGun/DELL-R14-3437-Hackintosh-for-OpenCore/blob/master/README.md)

### This is the first hackintosh boot that I maintain. It works well on my device dell-r14-3437. My configuration is listed below.

### CPU: i5 4200U frequency conversion is normal, 5 gears in total
### Video card: HD4400 is a strange HD4400. I haven't seen it happen. It has a good physique. However, it may be because of Weg that its current frequency is only 0.2Ghz. Can you help us solve it and see if it can reach 1GHz.
### Sound card: alc283 (ID: 88, created by me (xiaolegun), submitted by [daliansky] (https://github.com/daliansky) to send ID to vit9696. At this stage, MIC of headset can not be used normally, which may be different from the jack of headset. My headset is national standard, but Apple ALC may recognize American standard headset, but my headset works normally under win and Linux, Please study this problem. I've been working on this counterfeit sound card for a month and I'm really exhausted. So I'm going to GitHub to wait for your good news.
### Network & Bluetooth: Bcm94360HMM has no shielding pin but everything is normal. It's a Mini PCIe interface. You can go to Taobao and buy one by yourself. When I buy it, it's a 150RMB SF package.
### Touch panel & PS2 keyboard: I think it's normal. The touch panel can trigger the operation of three fingers at most, and PS2 keyboard is normal.
### Sleep can sleep at this stage, but there is a certain probability of sleep collapse. We have no solution to see if there is any way.

### I have solved a series of problems, such as battery display & sleep with cover closed (probability of collapse). The only problem is that sometimes the power is not cut off when the power is turned off. This problem occurs when the power is upgraded to 15.4. Please check it, thank you!

# This EFI can only be used when the CFG is unlocked. I use grub command to unlock it. Make sure your BIOS is upgraded to A12. Then use grub command to unlock the command as follows
``` 
1.setup_var_3 0x95
2.setuo_var_3 0x95 0x00
```

# About reward
<summary>WeChat&Alipay</summary>
<img src="https://github.com/xiaoleGun/DELL-R14-3437-Hackintosh-for-OpenCore/blob/master/WeChat.png" width="400px"  />
 
<img src="https://github.com/xiaoleGun/DELL-R14-3437-Hackintosh-for-OpenCore/blob/master/Alipay.png" width="400px" />

# This EFI contributor
- @[黑果小兵(daliansky)](https://github.com/daliansky)
- @天成小爱
- @黑果小兵微信群的所有人
- @云朵有点甜
- @小乐
- @[远景论坛](http://pcbeta.com)的大神
- @My (xiaoleGun)

# Warning！Warning！Warning！
## All of the above English is translated by Baidu translator. I will not give any feedback or compensation for any grammatical mistakes or national language discrimination.
