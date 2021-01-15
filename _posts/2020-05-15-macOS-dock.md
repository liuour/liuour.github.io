---
layout:     post
title:      Dock 栏设置隐藏和显示速度
subtitle:   快速隐藏和显示
date:       2020-05-15
author:     
header-img: img/bg-bowen.jpg
catalog: true
tags:
    - Mac
    - Dock栏
    - macOS
---

Mac 用户经常觉得底部 Dock 栏占用太多屏幕，办公不方便。设置自动隐藏后，发现隐藏和显示反应速度很慢。

可以通过终端，修改隐藏和显示时间 （单位 : 秒）

#### 默认

Dock 栏默认隐藏和显示为  1 秒。

```
defaults write com.apple.dock autohide-delay -int 1
```

#### 1. 修改命令

在【命令终端】输入或粘贴以下命令，按回车键（尾部时间数字可自定义）。

```
defaults write com.apple.dock autohide-delay -int 0.8
```

```
defaults write com.apple.dock autohide-delay -int 0.6
```

```
defaults write com.apple.dock autohide-delay -int 0.5
```

```
defaults write com.apple.dock autohide-delay -int 0
```

#### 2. 执行命令

不管修改上述哪一项，最后都要执行下面命令。

```
killall Dock
```