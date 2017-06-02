# supervisord在init.d的配置文件

直接复制脚本到/etc/init.d/下注意赋予执行权限

复制完后直接ntsysv配置启动 或者chkconfig --add supervisord 


其他项目也可以参考这样添加自启动

注意在脚本里加了python解释器的位置

