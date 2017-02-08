# 这是迅雷云监工docker版
@爱转角遇见了谁

***
## 版本说明
***
- :0208，为2月8日更新代码

***
## 2017.02.08 更新0208
***
2月8日更新源代码，说明见 https://github.com/hauntek/crysadm

应用了nginx反向代理，容器端口为80,监工端口4000
***

云监工程序docker版，以`tutum/ubuntu:trusty`为母镜像  

适用于所有docker平台  

外接卷路径`/var/lib/redis`，就是redis数据库存放目录  

容器端口云监工端口4000 SSH端口22，可以SSH到容器，root密码在日志查找  

此云监工源代码提取自 `https://github.com/hauntek/crysadm.git`  

不足之处：服务器时区不是北京时区，不能定时重启云监工，这些都需要ssh或控制台自己实现  

***

# 联系方式

***

Email：(hauntek@hotmail.com)

***
