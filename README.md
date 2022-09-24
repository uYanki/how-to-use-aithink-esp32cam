https://docs.ai-thinker.com/esp32-cam

https://blog.csdn.net/akk41397/article/details/106419396

arduino：https://www.jianshu.com/p/c1a69a6772f3

1.请保证模块输入电源至少5V 2A,否则图片会有几率出现水纹。

2.ESP32 GPIO32管脚控制摄像头电源，当摄像头工作时，请把GPIO32拉低。

3.由于IO0连接摄像头XCLK,使用时请把IO0悬空，请勿接高低电平。
