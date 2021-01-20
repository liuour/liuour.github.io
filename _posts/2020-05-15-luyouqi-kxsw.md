---
layout:     post
title:      路由器科学上网设置
subtitle:   订阅和单节点添加
date:       2020-05-14
author:     
header-img: img/bg-bowen.jpg
catalog: true
路由器: ture
tags:
    - 路由器
    - 科学上网
    - SSR
    - 机场订阅
---

大部分华硕、网件和领势路由器的高端型号都可以刷入梅林改版或官改。这个固件提供了软件中心功能，安装插件后支持配置订阅服务。

### 一、获取订阅地址

打开你所购买的服务，复制订阅链接。

[![Xnip2020-05-23_22-30-31](https://raw.githubusercontent.com/masonincn/tuchuang/master/uPic/Xnip2020-05-23_22-30-31.png)]()

### 二、配置科学上网

进入路由器后台，点击「软件中心」>「科学上网」>「订阅节点」。

> 第一次使用此插件，则会弹出此对话框，如果是单一节点，请点击「手动添加」。

![Xnip2020-05-27_16-45-30](https://raw.githubusercontent.com/masonincn/tuchuang/master/uPic/Xnip2020-05-27_16-45-30.png)

进入「更新管理」页面，将订阅链接粘贴至「订阅地址管理」处，点击「保存并订阅」。

![截屏2020-05-24-上午9.28.35](https://raw.githubusercontent.com/masonincn/tuchuang/master/uPic/截屏2020-05-24-上午9.28.35.jpg)

订阅完成后，页面会自动跳转到主页面，开启科学上网开关。

![截屏2020-05-23-下午10.49.38](https://raw.githubusercontent.com/masonincn/tuchuang/master/uPic/截屏2020-05-23-下午10.49.38.jpg)

### 三、附加设置

点击「更新管理」，将「规则定时更新任务」设置为「开启」，然后选择一个你可能不会使用网络的时间段，勾选所有规则，点击「保存设置」。

![截屏2020-05-23-下午10.56.08](https://raw.githubusercontent.com/masonincn/tuchuang/master/uPic/截屏2020-05-23-下午10.56.08.jpg)

DNS设置

![截屏2020-05-24-上午9.26.45](https://raw.githubusercontent.com/masonincn/tuchuang/master/uPic/截屏2020-05-24-上午9.26.45.jpg)

### 四、开启科学上网

点击「账号设置」，选择需要的节点，根据个人需求选择「模式」，点击底部「保存&应用」。

| 模式       | 介绍                           | 优点             | 缺点             | 消耗流量 |
| ---------- | ------------------------------ | ---------------- | ---------------- | -------- |
| gfwlist    | 被墙走SS，没被墙不走SS         | 防止迅雷和PT下载 | 需要维护         | ★        |
| 大陆白名单 | IP在中国不走SS，IP不在中国走SS | 无需维护         | 迅雷等BT下载走SS | ★★       |
| 游戏       | 在大陆白名单的基础上支持UDP    | 主机游戏NAT2     | 迅雷等BT下载走SS | ★★★      |
| 全局代理   | 所有网络都走SS                 | 全部出国         | 超级耗流量       | ★★★★★    |
| 回国       | 中国IP走SS                     | 适合人在国外使用 | -                | ★★       |

![截屏2020-05-23-下午11.04.28](https://raw.githubusercontent.com/masonincn/tuchuang/master/uPic/截屏2020-05-23-下午11.04.28.jpg)

* 国外链接：黄色 `✓`，表示成功。
* 国外链接：红色 `×`，表示失败，请更换节点。

---

网络可以“出国留学”后，请手机或电脑安装 Telegram 搜索联系 @**[masonzz](https://t.me/masonzz)**

> 注：[中国大陆 +86 号码注册不能私聊解决办法](https://masonme.github.io/2020/06/10/telegram/)

---

### Telegram 交流群

* 路由器交流群：[https://t.me/luyouqi](https://t.me/luyouqi)