# JLUNET
吉林大学的网络相关，目前还只有drcom

drcom脚本的话，需要python2.7环境，安装之后记得添加一下path，这个计算机专业的同学都比较熟悉。非CS的话可以搜下。

编辑器打开drcom.py，除了填写username,password之外，把ip,mac填写成你自己的以太网卡配置即可，host_name主机名可以改，也可以不改，这个没有关系。

之后以管理员运行命令提示符，进入到drcom.py所在目录下，python drcom.py运行即可。运行出现keep-alive2一行即成功，不要关闭命令行，最小化就行（因为要做心跳）。或者nohup python drcom.py& 在后台运行。
