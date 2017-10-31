# 来自Contiki RPL实现的Linux的RPL实现。

这个库不像应用于运行的Contiki RPL实现在主机，也不在微控制器上。应该是
使用6LoWPAN Linux内核实现。

## 编译说明:

make
sudo LD_LIBRARY_PATH=. ./examples/rpl-root-node -i lowpan0 -s ::1

## Status:
* 编译
* 在指定的接口上发送DIO.

## TODOs:
*接受和插入DAO。
*使用netlink，libnl或'ip route'设置路由。
