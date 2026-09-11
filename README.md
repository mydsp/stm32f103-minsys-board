# stm32f103-minsys-board —— 硬件题一：STM32F103C8T6 最小系统板

基于 STM32F103C8T6 的最小系统板：8MHz 晶振、LD3985M33R（3.3V/150mA LDO）、复位按键、SWD 与 USART1 合一调试口（2×5）、电源/功能指示灯、三位拨码开关（PA0/PA1/PA2）、用户按键（PB0/PB1）、TJA1050 CAN 接口（120Ω 终端电阻 + 3.81mm 端子）、GD25Q64 SPI Flash。
对应《G308 电控组 2026 夏季考核题》硬件第一题。

## 交付物

| 材料 | 文件 |
| --- | --- |
| 设计说明文档 | [硬1-设计说明文档.md](硬1-设计说明文档-最小系统板.md) / [PDF](硬1-设计说明文档.pdf) |
| 原理图 | [SCHC8T6.pdf](SCHC8T6.pdf) |
| PCB | [PCBC8T6.pdf](PCBC8T6.pdf)、[顶面](PCBC8T6(top).png) / [底面](PCBC8T6(button).png) |
| 网表 | [netlist-minsys.tel](netlist-minsys.tel) |

## 参考资料

- STM32F103C8T6 / LD3985 / TJA1050 / GD25Q64 数据手册
- [STM32F103C8T6 CAN 最小驱动板设计记录](https://blog.csdn.net/2301_80165137/article/details/147024209)
- [STM32 最小系统电路设计教学](https://blog.csdn.net/black_sneak/article/details/138352997)
