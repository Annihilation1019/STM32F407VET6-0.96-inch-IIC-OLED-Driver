# 立创天空星 stm32f407vet6 开发板 移植 0.96寸 OLED SSD1306 显示屏模块

- 根据江协科技和模块厂家提供的资料，移植了0.96寸OLED SSD1306显示屏模块的驱动程序，可以在立创天空星stm32f407vet6开发板上使用。
- 支持硬件 IIC 和软件 IIC 两种方式。需在 OLED.c 启用对应的宏定义。
- 四种字体大小，8x6，12x6，16x8，24x12。