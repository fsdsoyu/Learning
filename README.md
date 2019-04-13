# 说明

此版本为树莓派运行版本，需要安装的软件同树莓派版使用说明。

树莓派版安装python包有点蛋疼，现在记不起来了，我也是第一次玩树莓派，自己百度一下，应该可以解决的，遇问题也可以在Issues上留言。

我曾在ubuntu服务器版中运行过源代码，因为是阿里云服务器，最近没敢实验，使用基本同树莓派，安装chrome和chromedriver自行百度一下，VPS比树莓派好用，推荐使用64位linux。


# 无人职守使用

使用指令:crontab -e

在文件末尾加上

00 6 * * * cd ~/learn && python3 /home/pi/learn/learn.py > /dev/null 2>&1

cd 及python3 后的路径，要根据自己文件存放的位置自行调整。
