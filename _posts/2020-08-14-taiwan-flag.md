---
layout:     post
title:      Mac 显示台湾区旗
subtitle:   
date:       2020-08-14
author:     
header-img: img/bg-bowen.jpg
catalog: true
tags:
    - macOS
    - 台湾

---

## 1. 打开隐藏文件

* 菜单栏「前往」>「前往文件夹」，输入以下路径并前往。
```
/Library/Preferences/.GlobalPreferences.plist
```
* 按 `Command-Shift-.` 三个组合键，显示隐藏文件`.GlobalPreferences.plist`。

![001](https://tvax1.sinaimg.cn/large/008aobiRgy1ghqs0mo83ej31j60yk7l3.jpg)

## 2. 修改地区

打开 `.GlobalPreferences.plist` 将「CN」改为「TW」，保存并重启 Mac，即可显示台湾区旗。

![](https://tvax2.sinaimg.cn/large/008aobiRgy1ghqs6v3q9uj317m0jg0wh.jpg)


`注：如果提示没有权限修改，继续以下操作，反之请忽略。`

## 3. 查看 SIP 状态

打开「终端」输入 `csrutil status`，如果是「已开启」则需要关闭 SIP。

**enabled 已开启：**
```
System Integrity Protection status: enabled.
```
**disabled 已关闭：**
```
System Integrity Protection status: disabled
```



## 4. 关闭 SIP

* Mac 开机立即按住 `Command-R`，当显示图标时松开按键。
* 等待进入「实用工具」窗口，菜单栏「实用工具」选择「终端」。

![](https://tva1.sinaimg.cn/large/008aobiRgy1ghrjsbwvv2j30v406pq5u.jpg)

* 输入 `csrutil disable` 按回车键。然后点击左上角图标，重启 Mac。

![](https://tva4.sinaimg.cn/large/008aobiRgy1ghrjt4052tj30v40jggpa.jpg)




## 5. 修改文件夹权限

* 重启后，右击文件夹「显示简介」，解锁右下角黄色锁，将「只读」改为「读与写」。
* 打开 `.GlobalPreferences.plist` 文件修改后，会发现可以保存了。

![002](https://tva2.sinaimg.cn/large/008aobiRgy1ghqsahfkypj322w1cuwre.jpg)

### Telegram 交流群

* macOS 交流群：[https://t.me/macosqun](https://t.me/macosqun)

