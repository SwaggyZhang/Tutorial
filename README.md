# Windows 10 + Ubuntu 双系统安装、深度学习环境配置及排错指南

## 前言
本教程为Windows10安装Ubuntu18.04 (x64)双系统教程，基于[此教程](https://www.cnblogs.com/masbay/p/11627727.html)进行修改。

进一步添加了Anaconda安装、Pytorch安装、显卡三件套 (nVidia Driver + CUDA + cuDNN) 安装及配置

## Tips
由于电脑品牌多样，碰到问题可能本教程并未涵盖，大家可以自行搜索后尝试解决，并且可以将自己问题和解决方法提交至issue，从而使教程更加丰富

## 一、查看电脑信息
### 1. 查看BIOS类别
使用"Win + R"组合键调出运行窗口，在对话框输入"msinfo32"，出现下述界面，以查看BIOS模式：

![image](.\figures\check_BIOS.png)

确定BIOS模式为UEFI. 新电脑大多数为UEFI模式，本教程仅基于UEFI模式的BIOS进行安装。

### 2. 查看硬盘
在左下角Win Logo上点击鼠标右键，进入磁盘管理：

![image](.\figures\check_disks.png)
