# 88W8782 Module BaseBoard

- 模块简介

	- 芯片组：Marvell 88W8782

	- 接口类型：SDIO（1bit/4bit）

	- 天线类型：外置天线

	- 协议/标准：IEEE 802.11b, IEEE 802.11g, IEEE 802.n (1T1R Modes)

	- 频率范围：2.400~2.4835GHz

	- 频道：1~11 (美国, 加拿大), 1~13 (欧洲), 1~14 (日本)

	- 调制模式：

		- 802.11b： DSSS (CCK, DQPSK, DBPSK)
		- 802.11g/n： OFDM (BPSK, QPSK, 16QAM, 64QAM)

	- 无线速率

		| **802.11**  | **2, 1 Mbps**                        |
		| ----------- | ------------------------------------ |
		| **802.11b** | **11, 5.5Mbps**                      |
		| **802.11g** | **54, 48, 36, 24, 18, 12, 9, 6Mbps** |
		| **802.11n** | **150Mbps（最大）**                  |

	- 发射功率：802.11b/g/n： 13 ±1dbm

	- 无线安全：64/128-bit WEP, WPA/WPA2, WPA-PSK/WPA2-PSK (TKIP/AES)

	- 功耗

		- 休眠状态： 0.6mA；
		-  接收数据： 120mA； 
		- 发送数据： 180mA

	- 实物图片

		![ModuleFront](/Picture/ModuleFront.png)

		![ModuleBack](/Picture/ModuleBack.png)

- 底板说明

	- EDA设计软件：Cadence Allegro 16.6

	- 天线：2.4G板载天线，可以根据需要自行更改为天线连接座或二者兼容；

	- 原理图

		![](/Picture/SCH.png)

	- PCB（模组封装为正面视图，模块正面左上角对应丝印圆点安装）

		![](/Picture/PCB.png)