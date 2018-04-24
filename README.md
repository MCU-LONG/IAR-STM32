# IAR-STM32
适用于IAR工具链的STM32库文件

IAR-KEIL_killl.bat：IAR和KEIL通用的kill文件，用于清除编译生成中间文件。

HEX_stm32f103xC.icf：用于远程升级，设置烧写的ROM和RAM地址。

/Libraries/CMSIS/startup/startup_stm32f10x_xxx.s：用于STM32F1xxx的启动文件，只适用于IAR工具链，KEIL下的启动文件不可用。为了避免编译出错，在
startup_stm32f10x_hd.s文件中加入NOROOT。

