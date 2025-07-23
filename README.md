# npc-client
一键最小化启动npc客户端，使用SilentCMD作为启动件
# 使用方法
1.下载npc客户端


2.下载本脚本文件


3.解压npc客户端


4.解压本脚本


下载本文件解压后放入到nps的文件夹内


文件内容：

start.bat

SilentCMD.exe
# 配置文件修改
打开npc的配置文件，修改以下内容


server_addr=你的服务器地址:端口


conn_type=通信方式可选kcp和tcp，默认tcp


vkey=客户端服务器通信唯一验证密钥，可在服务器web页面中添加客户端时自己输入获得


# 试运行
使用cmd或者Windows终端或者WindowsPowerShell进行试运行测试
进入npc文件夹内后，在地址栏输入cmd可以打开cmd 运行命令 start npc.exe
鼠标右键选择在终端打开，可以打开终端，运行命令./npc
鼠标右键选择在此处打开powershell窗口，可以打开powershell口，运行命令./npc




