# 2021-emb

本程序为2021年嵌入式竞赛龙芯赛道代码，旨在打造一个简易的本地的智能家居系统



# 实现功能

rpi读取传感器数据，通过modbus-tcp与龙芯派交流数据，龙芯派根据数据控制IO口进而控制继电器和用电器，以及给微信推送信息（使用server酱）。

