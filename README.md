# netease-cloud-music
可用于ubuntu 18.04的网易云音乐

这些问题在新版本1.2.0似乎已经修复了，请各位到[官网](https://music.163.com/#/download)下载安装1.2.0版本

[下载Release包](https://github.com/InNoob/netease-cloud-music/releases)

要安装deepin-wine看这里：可用于deb包系的deepin-wine一键安装脚本(可用于安装TIM,QQ,迅雷等软件)

[deepin-wine-installer](https://github.com/InNoob/deepin-wine-installer)

####  1.1.1+rebuild.release-2
> ####  修复了上个版本重复打开会导致客户端启动卡死的问题
> ####  解决了安装在机械硬盘上可能无法启动的问题
> ####  加快了启动速度
> ####  已知问题：在终端使用命令启动有几率无法启动

####  1.1.1+rebuild.release-1
> ####  基于 1.1.0 网易云音乐修改代码重新构建
> ####  修复了在ubuntu18.04下可以正常安装但无法打开使用的bug
> ####  修复了文件和链接库权限问题，该问题导致qt加载文件失败
> ####  解决了上个版本在状态栏无法使用mpris协议面板的问题，但又重新引入了vlc客户端依赖
> ####  将文件从/usr/bin/和/usr/lib/迁移到/opt/netease-cloud-music/目录，来避免可能是gnome-shell有沙盒机制所导致的问题

#### 1.0.1+rebuild.fixbug-2
> ####  基于 1.0.0 的网易云音乐修改代码重新编译打包
> ####  修复了在ubuntu18.04下可以正常安装但无法打开使用的bug
> ####  移除了vlc客户端的依赖，安装之后不再捆绑vlc
