---
title: Grove AI HAT USB 驱动安装
keywords: maixpy, k210, AIOT, 边缘计算
desc: maixpy  FT2232 USB 驱动安装
---


## Linux

Linux 不需要装驱动，系统自带了，使用 `ls /dev/ttyUSB*` 即可看到设备号

## Windows

`Windows` 用户需要安装 `FT2232` 的驱动。

- USB 驱动: **FT2232** ->[下载链接点这里](https://dl.sipeed.com/shareURL/MAIX/tools/ftdi_vcp_driver)

我们在拿到 MaixPy 开发板并连接到电脑的时候, 可以打开设备管理器查看串口驱动是否已经安装,打开设备管理器的方法有:
- 此电脑(右键) -> 属性 -> 设备管理器
- 开始菜单(右键) -> 设备管理器
- 控制面板 -> (搜索)设备管理器

<img src="../../../assets/get_started/win_device_1.png" height="400">

1. 当我们的系统是 Windows 10 系统,系统则会帮我们自动安装驱动，而如果是旧版 Win7，win8 系统，我们就需要自己手动安装 USB 驱动:
    ![](../../../assets/get_started/win_device_2.png)

2. 打开上一节的的链接下载驱动
    ![](../../../assets/get_started/win_device_3.png)

3. 点击安装
    ![](../../../assets/get_started/drives.gif)

4. 安装完成之后,可以在设备管理器看到已经识别到两个串口设备了(其中只有一个串口可用)
    ![](../../../assets/get_started/win_device_4.png)