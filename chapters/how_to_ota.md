# 如何更新固件
## 什么是OTA？
OTA (Over The Air Programming)，空中升级，即通过无线传输的方式对设备进行固件升级。我们的键盘控制器采用这种方式进行固件更新。下面介绍具体操作流程。

## 如何获取最新固件
关注微信公众号 `XORLink`，回复消息 “固件” 二字即可获取最新固件下载链接。

![公众号二维码](../images/wechat.JPG)
## 固件更新流程
请看[操作视频](https://mp.weixin.qq.com/s/IxZT1mpbO_71S2s5kv5ndQ)，这里以 iOS 系统进行演示。

具体操作步骤如下：

1. 确保手机已经安装 nRF Toolbox 应用程序。
2. 选择 nRF Toolbox 应用程序打开我们待更新的固件包。
3. 在键盘上按 `Fn + 右 Alt + T` 组合按键，使键盘进入 OTA 模式，此时 LED 指示灯常亮。
4. APP 上点击 “Connect” 按钮，选择 HHKB_DFU。然后点击待更新的 zip 固件包。最后点击 Upload ，等待升级完成即可。

升级完成后，键盘会回到进入 OTA 模式前的状态。

**注意：更新过程中，千万不要按键盘侧面的 Wake Up 按键。**

