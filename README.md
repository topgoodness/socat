Socat一键安装脚本
-----------
系统要求：支持CentOS 6+ 、Debian 7+、Ubuntu 14+

脚本说明：脚本默认开启`UDP`、`TCP`转发，带开机自启功能，且一次只能转发单个端口，如果想转发多个端口请重复运行本脚本。

使用`root`运行以下命令：

    wget https://raw.githubusercontent.com/topgoodness/socat/refs/heads/master/socat.sh && bash socat.sh

按要求输入本地服务器端口，要转发的目标端口和服务器IP即可！

#如果你要用本地服务器的1000端口转发IP为1.1.1.1服务器的6666端口，那就依次填入指定参数。
请输入本地端口:1000
请输入远程端口:6666
请输入远程IP:1.1.1.1（可以使用域名）
