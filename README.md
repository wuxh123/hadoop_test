# 单机版虚拟机hadoop测试环境
## 目前只装完hadoop和hbase，觉得装环境麻烦的朋友或者想学习的同学可以在这上面直接测试开发。

## 安装过程 请参考
https://github.com/wuxh123/my_bigdata

## 虚拟机地址

##虚拟机密码:wuxh wuxh
## hadoop账户密码 hadoop hadoop

## hadoop web url
http://192.168.64.128:50070

## 启动hadoop
./usr/local/hadoop/sbin/start-all.sh

## 启动hbase
/home/hbase/hbase-2.0.5/bin$ sudo ./start-hbase.sh

## 停止hbase
/home/hbase/hbase-2.0.5/bin$ sudo ./stop-hbase.sh

## 进入hbase环境
wuxh@ubuntu:/home/hbase/hbase-2.0.5/bin$ sudo ./hbase shell
