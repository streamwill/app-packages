# app-packages
some applications on ubuntu
使用v2ray科学上网的话，windows平台我们可以使用clash，v2rayN等软件，mac端的话可以使用clashX等，但是对于linux系统，我们的选择就比较少了，今天介绍一款linux上很好用的图形话界面科学上网工具-Qv2ray。

🌟 Linux/Windows/macOS 跨平台 v2ray GUI 🔨 使用 c++ 编写，支持订阅，扫描二维码，支持自定义路由编辑 🌟。使用 Qt 框架的跨平台 v2ray 客户端。支持 Windows, Linux, macOS。

这是github页面的作者简介，下面来看下linux上面配置教程。-本教程基于Ubuntu哦。其他Linux平台类似。

1：下载V2ray客户端，这里以最简单的AppImage文件为例,直链下载：

https://github.com/Qv2ray/Qv2ray/releases/download/v1.99.6/Qv2ray-refs.tags.v1.99.6-linux.AppImage

或者可以去GitHub上下载：https://github.com/Qv2ray/Qv2ray/releases/tag/v1.99.6 选择下图文件
![image](https://user-images.githubusercontent.com/32317492/129653602-9eeb1bbc-f16f-42bb-9d5a-c36255afbdcb.png)


注意：建议下载1.99.6及以上版本，其它版本可能出现找不到openssl库。

2：下载核心文件，直链下载：

https://github.com/v2ray/v2ray-core/releases/download/v4.22.1/v2ray-linux-64.zip

或者可以去GitHub上下载：https://github.com/v2ray/v2ray-core/releases/ 选择下图文件

3:进入v2ray下载的根目录，执行以下命令：

sudo chmod +x ./Qv2ray-refs.tags.v1.99.6-linux.AppImage

4:仍然在v2ray根目录下打开终端，输入以下命令：

sudo ./Qv2ray-refs.tags.v1.99.6-linux.AppImage

执行4后会出现主界面，点击首选项
5:常规设置里面按照图示操作,最后点击ok保存：

6：回到主界面，点击订阅：

然后按照下图要求填入相应内容,然后点击ok：

进入网站->个人中心，按照下图说明复制链接到上图中：

将软件的代理模式打开，如下图所示：

7:一切准备好后点击主界面的连接，开始科学上网
