# Chia集群绘图管理系统

#### 功能介绍


整套系统分为3个部分软件相结合而成。

ChiaTools 调用Chia客户端进行自动绘图的，也可以单机运行自动绘图。

ChiaDiskServer 存储机磁盘管理 ,同时向控制中心上报可以存储的磁盘分区。

ChiaServer 集群管理控制中心，调度存储机的存储分区和统计绘图机的进度状态等信息

-------------------------------

监控绘制好的图回传到存储机磁盘的速度，可及时监控网络故障。软件本身不访问外网，可脱离外网运行，

（脱离外网的方法：任何机器不要设置网卡网关地址，这样内网依然正常通讯，可正常内网传输通讯）所以你完全可以放心使用！

（绘图机安装官方chia软件，但是切记不要登录任何账户，只安装，安装好后关闭chia就行咯，因为绘图会CMD调用chia程序）

-------------------------------
#### 矿场实践使用案例

绘图客户机130台，自动绘图通过局网传输回存储服务器。 系统WIN10系统

存储服务器30台，单台24*16T存储，用于实时接收绘图机回传的文件。 系统WIN2019，共享不会有限制，同时可安装chia客户端，不要登录账户，设置网络收割机可同时收割。

控制台1台，查看调试，远程，调度整体的绘图进度，存储机存储盘分配，绘图机温度监控等等。系统系统WIN2019,可用于客户端软件升级更新,(当然你整合到存储机上也可以)


-------------------------------

本软件系统（永久免费）    软件运行平台 WIN10/WIN2008/WIN2019等系统

#### QQ群 754348914


![ChiaServer](https://github.com/gujunsu/ChiaTools/blob/main/ChiaServer20210610142343.png?raw=true "ChiaServer20210610142343.png")

![ChiaDiskServer](https://github.com/gujunsu/ChiaTools/blob/main/ChiaDiskServer20210601164459.png?raw=true "ChiaDiskServer20210601164459.png")

![ChiaTools](https://github.com/gujunsu/ChiaTools/blob/main/ChiaTools20210601164353.png?raw=true "ChiaTools20210601164353.png")



