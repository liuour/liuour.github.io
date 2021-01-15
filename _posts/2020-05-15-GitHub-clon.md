---
layout:     post
title:      GitHub Desktop Clone 速度慢
subtitle:   提升克隆速度
date:       2020-05-15
author:     Mason
header-img: img/bg-bowen.jpg
catalog: true
tags:
    - GitHub
    - Clone
    - 效率
---

### 步骤1 查看地址和端口
* 打开 ShadowrocketX-NG-R8 代理工具，点击「高级设置」。
* 查看 Socks5 地址和端口（我的是`127.0.0.1:1086`）。

![socks5](https://raw.githubusercontent.com/masonincn/tuchuang/master/uPic/socks5.jpg)


### 步骤2 执行代码
在【命令终端】输入或粘贴以下命令，按回车键。

```
git config --global http.https://github.com.proxy socks5://127.0.0.1:1086
git config --global https.https://github.com.proxy socks5://127.0.0.1:1086
```
打开 GitHub Desktop 进行 Clone 测试，速度变快很多。

---
### 恢复初始状态

在【命令终端】输入或粘贴以下命令，按回车键。

```
git config --global --unset http.https://github.com.proxy socks5://127.0.0.1:1086
git config --global --unset https.https://github.com.proxy socks5://127.0.0.1:1086
```

