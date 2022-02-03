# DELL-R14-3437-Hackintosh-for-OpenCore

[English](https://github.com/xiaoleGun/DELL-R14-3437-Hackintosh-for-OpenCore/blob/master/README-EN.md)

[Chinese](https://github.com/xiaoleGun/DELL-R14-3437-Hackintosh-for-OpenCore)

> Update date: 2022.02.03

> OpenCore Version: 0.7.4

> This is the first Hackintosh boot I maintain, it runs fine on my device DELL-R14-3437,my configuration is listed below.

|Configuration| |Status|
|--| --- | --- |
|CPU|i5 4200U|Locked Maximum Frequency|
|IGPU|HD 4400|HDMI audio/video normal|
|Audio|ALC283|2-in-1 Mic not working properly|
|NIC/Bluetooth|BCM94360HMB|Everything works fine with spacing and pickup|

## Problem
1, may encounter shutdown without power, and for the time being do not know what causes it.

2, sleep sleep death, which is a common phenomenon.

3, reboot sound from win hot may not play sound properly, because windows loaded audio does not apply to mac.

## Unlock CFG
> I have found this vintage machine unlock node on about Feb 24, 2020, and now share it with you. Please use Grub shell to enter the following command
``` 
setup_var_3 0x95
setuo_var_3 0x95 0x00
```
## Reward
<summary>WeChat & Alipay</summary>

<img src="https://github.com/xiaoleGun/DELL-R14-3437-Hackintosh-for-OpenCore/blob/master/WeChat.png" width="400px" />
<img src="https://github.com/xiaoleGun/DELL-R14-3437-Hackintosh-for-OpenCore/blob/master/Alipay.png" width="400px" />

# Contributors
- xiaole 
<! -- Girls I used to like -->
