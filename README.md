# aria2-for-ubuntu20.04
关于Ubuntu下配置aria2的必要文件

一个关于aria2配置在ubuntu20.04的说明

首先要安装aria2c
    
  sudo apt-get install aria2c

然后将aria2.sh-master和aria2c文件夹放入~/.local/文件夹下

并将aria2NG.desktop文件放入/usr/share/applications/文件夹下

  sudo cp aria2NG.desktop /usr/share/applications/ 

最后会在gnome启动器中多一个小火箭的图标，点击图标即可启动aria2NG
