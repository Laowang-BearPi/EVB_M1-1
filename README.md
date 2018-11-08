# 《EVB_M1 手把手教程》
------

**NB-IoT**毫无疑问是2018年物联网领域的重头戏，它让万物联网变得更进一步，承载着大家对物联网更深一步探索的希望。**《EVB_M1》开发套件**将让你对NB-IoT领域的学习变得更为便捷。首先，我将与大家一起来探索一下几个问题：
>* 什么是NB-IoT ？
>* 什么是物联网的南向北向？
>* NB-IoT如何实现数据上传？
>* NB-IoT如何实现数据下发？

**工欲善其事必先利其器**，探索问题之前，先和大家介绍一下我们开发过程中使用的工具：**《EVB_M1》开发套件**。EVB_M1是为学习NB-IoT量身打造的一个开发利器，开发板用STM32L4超低功耗MCU作为主控，通讯模组采用BC35-G全频段NB-IoT模组，具有可视化OLED数据展示、按键输入等人机交互功能。不仅如此，它还拥有IoTCluB专用EXT_X扩展接口，可以很便捷的模拟多种应用场景，如：**温湿度**、**光照**、**烟雾报警**、**甲醛检测**、**GPS定位**等。EXT_X扩展板接口还具有丰富的接口资源，如常用的UART、I2C、SPI、CAN、GPIO、ADC、DAC等。

>* 接口定义：
>
| 项目     		| 名称 		|            	 数量|
|---------------|:---------:|:------------------:|
|CAN			|CAN总线接口 | 					1|
|UART			|串行通信	|					2|
|SPI			|	串行SPI |					1|
|GPIO			|	通用GPIO|					3|
|ADC			|模拟输入接口|					1|
|DAC			|模拟输出接口|					1|
|IIC			|	 IIC接口|					2|
|VCC_5.0		| 	5.0v供电|					1|
|VCC_3.3		|	3.3v供电|					1|

>* 支持扩展板：
>
| 项目     		| 名称 		|             应用案例|
|---------------|:---------:|:------------------:|
|EXT_温湿度		|温湿度扩展板| 			  智慧农业|
|EXT_烟感		|  烟雾扩展板|			  智慧消防|
|EXT_GPS  		|  定位扩展板|   			 Trace跟踪|
|EXT_光照		|  光照传感器|   			  智慧路灯|
|EXT_开关		|  继电器开关|			  智能家居|
|EXT_WiFi		|无线设备接入|			  智能家居|

>*产品特点
>
| 名称     		|规格  		|             	 说明|
|---------------|:---------:|:------------------:|
|低功耗处理器		|STM32L431Rx|Cortex-M4内核		 |
|				|			| 80MHz主频			 |
|				|			| 8nA掉电模式		 |
|				|			| 高速flash			 |
|低功耗OLED		|128*64		|运行模式10mA功耗		 |
|				|			|低功耗模式2uA		 |
|供电方式		|USB+锂电池	|锂电池3.7V			 |
|				|			|MicroUSB			 |
|NB模组			|BC95、BC35-G|BC95-Bx:单一频段	 |
|				|			|BC35-G	:全频段		 |
|两种SIM卡接入	|NB卡、eSIM	|普通封装的NBSIM卡	 |
|				|			|芯片封装的NBSIM卡	 |
|功耗测量板		|0.01mA精度	|					 |

```
##什么是NB-IoT?
1.
2.
```
##什么是物联网的南向北向


##NB-oT如何实现数据上传？


##NB-IoT如何实现数据下发？
