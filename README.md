CKB01 5GCPE 是一个很奇葩的配置

IPQ8072A的CPU，

QCA8075 千兆网口，
qcn5024  qcn5054 无线，
sdx55 5G模块，
spi 闪存 1.8v 4M，
系统是基于QSDK改的，系统存放在X55模块的闪存里，
在X55模块里面虚拟一个29M的磁盘用来放openwrt的固件uImage-initramfs.itb；

op固件本身不能保存设置，所有设置又会写入x55模块里；
有关模块5G上网的配置都是加密的;
暂时写到这里.
