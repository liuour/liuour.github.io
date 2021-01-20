---
layout:     post
title:      macOS 系统安装方法
subtitle:   网络安装和从时间机器备份恢复安装
date:       2020-05-15
author:     
header-img: img/bg-bowen.jpg
catalog: true
tags:
    - macOS
    - 时间机器
---

### 方案一、网络安装

#### 1.1 macOS恢复启动

* 开机立即按住 `Command-R` ，看到旋转的地球或  标志时，松开按键。
* 等进度条走完，当看到「macOS 实用工具」窗口时，表示 macOS 恢复功能启动。

#### 1.2 抹掉磁盘

>注：如果不格式化磁盘跳过步骤 `1.2` 和 `1.3`，从步骤 `1.4` 开始。

* 「macOS实用工具」窗口中选择「磁盘工具」，点按【继续】。
![r34iuby7GvlDjTs](https://i.loli.net/2020/04/10/r34iuby7GvlDjTs.png)

#### 1.3 选择系统硬盘（或更换的新硬盘），点击「抹掉」，完成后返回到「macOS实用工具」界面。

  > * 名称：自定义。
  > * 格式：APFS。
  > * 方案：GUID 分区图。
  > * 点选「抹掉」。

![K8gaYOmbWTkHwI9](https://i.loli.net/2020/04/10/K8gaYOmbWTkHwI9.png)

#### 1.4 安装 macOS

* 从「macOS实用工具」窗口中选取「重新安装 macOS」。
* 然后点按“继续”，按照屏幕上的说明来选取硬盘并开始安装。
  `注：不要将 Mac 处于睡眠或合上上盖， 直到安装完成。安装过程中，可能会多次重新启动并显示进度条。`

![8ioXAzFv53hMN1J](https://i.loli.net/2020/04/10/8ioXAzFv53hMN1J.jpg)

> 注：如果从未升级至 macOS Sierra 10.12.4 或更高版本，则 macOS 恢复功能的方法会不同：

* `Command-R`  仍是通过 macOS 恢复功能启动的推荐方法。
* `Option-Command-R`  会安装 Mac 随附的 macOS 或与它最接近且仍在提供的版本。
* `Shift-Option-Command-R`  不可用。

---

### 方案二、时间机器恢复

#### 2.1 进入启动界面

* 开机立即按住 `Command-R` ，看到旋转的地球或  标志时，松开按键。
* 等进度条走完，当看到「macOS 实用工具」窗口时，表示 macOS 恢复功能启动。

#### 2.3 备份恢复

* 点击「从时间机器备份进行恢复」，选择硬盘和备份系统文件，按提示操作完成 macOS 系统安装。
![b2yQzutAo5q8DvB](https://i.loli.net/2020/04/10/b2yQzutAo5q8DvB.png)

### Telegram 交流群

* macOS 交流群：[https://t.me/macosqun](https://t.me/macosqun)