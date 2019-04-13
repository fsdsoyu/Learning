# 说明

此版本，为树莓派下实验可行，需要安装的软件同树莓派版使用说明。

我曾在ubuntu服务器版中运行过源代码，因为是阿里云服务器，最近没敢实验，使用基本同树莓派，安装chrome和chromedriver自行百度一下。

# 无人职守使用

使用指令:crontab -e

在文件末尾加上

00 6 * * * cd ~/learn && python3 /home/pi/learn/learn.py > /dev/null 2>&1

cd 后的路私，要根据自己文件存放的位置自行调整。
