# surfacepro7-oc
surfacepro7-hackintosh

### 本机硬件
- surface pro 7
- CPU: 1065G7
### 已测试系统
- 10.15.5
- 10.15.6
- 11 bate 6

### 已知兼容设备
- surface pro 7 i5

### 已驱动
- 显卡
- wifi
- 蓝牙
- 键盘
- 触摸板(设置中看不到触摸板但是手势等可用)。

### 未驱动
- 电源管理

### 已知问题
- hidpi下会闪屏，切换到其他分辨率或接入外接1080P显示器即可解决闪屏。

### 触摸板命令行设置：
- 设置轻触点击
  defaults write com.apple.AppleMultitouchTrackpad Clicking -bool true
  sudo defaults write com.apple.driver.AppleBluetoothMultitouch.trackpad Clicking -bool true
  sudo defaults -currentHost write NSGlobalDomain com.apple.mouse.tapBehavior -int 1
  sudo defaults write NSGlobalDomain com.apple.mouse.tapBehavior -int 1

- 连续双击选中
  defaults write com.apple.AppleMultitouchTrackpad Dragging -bool true
  sudo defaults write com.apple.driver.AppleBluetoothMultitouch.trackpad Dragging -bool true

## 感谢：
- @zxystd(wifi、蓝牙驱动) https://github.com/OpenIntelWireless/itlwm
- @0xFireWolf(驱动cd clock、解决sku、解决dvmt60M等问题) https://github.com/0xFireWolf/WhateverGreen
- 以及各类驱动提供者。
- surface 黑苹果先驱者

![image](https://github.com/ati46/temp/blob/master/Snipaste_2020-09-07_16-03-19.png?raw=true)
