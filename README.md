# DemoRaspberrypi

初始用户名 pi，密码为 raspberry

获取树莓派ip地址：ifconfig

树莓派 VNC Viewer 远程桌面配置教程： 
https://shumeipai.nxez.com/2018/08/31/raspberry-pi-vnc-viewer-configuration-tutorial.html

树莓派手动玩(开启SSH,VNC)： 
https://www.jianshu.com/p/a011d01bdf51

在树莓派上安装vnc服务端（debian）： 
sudo apt-get install tightvncserver

手工启动： 
tightvncserver

New 'X' desktop is raspberrypi:1

TightVNC xxx.xxx.xxx.xxx:1

PWD: 123456

--启用树莓派系统自带的VNC服务

sudo raspi-config

Interfacing Options

VNC Viewer:  

如果要修改树莓派的分辨率，可以在终端运行 sudo raspi-config 进入设置界面设置操作。

-- 配置音频输出方式

sudo raspi-config

Audio 3.5mm

sudo shutdown -h now
