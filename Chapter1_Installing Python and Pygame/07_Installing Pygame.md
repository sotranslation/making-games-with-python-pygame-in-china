# 安装Pygame

Python没有内置安装Pygame。和Python一样，Pygame是免费的。你可以下载安装Pygame，像下载和安装Python编译器一样简单。在浏览器，访问[这个地址](http://pygame.org )，网页左边点击**Downloads**链接。本书假定你是windows操作系统，但是同样的Pygame程序适用于任何操作系统。根据你的操作系统和Python版本，下载对应的Pygame安装器。

你不想下载Pygame源代码，而是想要针对你自己操作系统的Pygame二进制安装文件。对于windows，下载*pygame-1.9.1.win32-py3.2.msi*文件。（这个Pygame基于windows上Python的3.2版本。如果你安装了不同的Python版本（例如2.7 或者 2.6），那么你需要下载对应版本的.msi文件）。写这本书时，Pygame的当前版本是1.9.1。如果你在官网发现了更新的版本，可以下载安装新版的Pygame。

对于Mac OS X，下载对应Python版本的.zip或者.dmg文件，并运行它。

对于Linux，打开终端并运行```sudo apt-get install python-pygame```。

在windows上，上级下载的文件安装Pygame。检查Pygame是否正确安装，输入以下命令：
```
>>> import pygame
```
敲击回车键之后，没有任何展示，Pygame算是已经成功安装。如果出现错误*ImportError: No module named pygame*，试着重新安装Pygame（确保输入正确的 *import pygame*）。

本章提供五个小程序演示Pygame提供的不同功能。最后一章，将用这些功能完成一个基于python语言使用Pygame的完整游戏。

从这本书的[网站](http://invpy.com/videos)可获得安装Pygame的演示视频。