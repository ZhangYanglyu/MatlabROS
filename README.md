# 学习笔记

## 环境配置

在 Ubunutu 系统上安装 Ros 软件，在 Windows10 上安装 Matlab 软件。

Ubuntu:

* 使用 ifconfig, 查看 Ubuntu 的 ip 地址，比如 ip 地址为 192.168.1.111

* 将 ROS 所用到的环境变量添加到 ~/.bashrc 文件中

* 设置防火墙规则 sudo ufw allow from 192.168.1.106

Matlab:

* 查看 Windows10 的 ip 地址，比如 ip 地址为 192.168.1.106

* 关闭 Windows10 的防火墙，允许入站访问

* setenv('ROS_MASTER_URI','<http://192.168.1.111:11311>')

* rosinit
