https://docs.ai-thinker.com/esp32-cam

1. 请保证模块输入电源至少5V 2A,否则图片会有几率出现水纹。

2. ESP32 GPIO32管脚控制摄像头电源，当摄像头工作时，请把GPIO32拉低。

3. 由于IO0连接摄像头XCLK,使用时请把IO0悬空，请勿接高低电平。
4. 确保 wifi 是 2.4G 频段的（esp32 不支持 5G 频段）

