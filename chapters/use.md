# 使用说明
## 连接
### 蓝牙连接
当控制板接上电池后，蓝色LED灯开始闪烁。表示控制板开始工作，等待蓝牙设备进行连接。接下来，以macOS平台演示如何连接。
1.首先打开蓝牙偏好设置，可以看到名字以“HHKB”开头的键盘设备，这就是我们的键盘。
![bluetooth_config](https://hhkb-1257557502.cos.ap-chengdu.myqcloud.com/schedule/bluetooth%20config.png?q-sign-algorithm=sha1&q-ak=AKIDjCbgndoeKjPcbBW13EOmflR4urR4jxnU&q-sign-time=1555751262;1555753062&q-key-time=1555751262;1555753062&q-header-list=&q-url-param-list=&q-signature=ab5c84f01d2e6f0a33908467241cf90e2ab10540&x-cos-security-token=c239958bd8a7689c50eb08ba3ce87941ba7ffd5710001)

2.点击连接，等待其连接完成，显示已连接。
接下来，按一下command+tab键，若可以进行任务切换，说明键盘可以使用了。

### USB连接
默认情况下，键盘通过蓝牙输入。若想切换到USB输入，首先连接上USB，然后按 “Fn+U”组合键（U为USB的首字母），即可切换到USB输入。同理，按下“Fn+B”组合键（B为Bluetooth的首字母），即可切换到蓝牙输入。

## 功能说明
1. 连续30分钟无按键操作，键盘将主动断开连接并进入待机状态，此时耗电量极低，可忽略不计。
2. 待机状态下，键盘不能使用。通过按侧面的Wake Up键可唤醒键盘以继续工作，此时会自动连接到之前的设备。
3. 在已连接设备的情况下，若要连接到其它设备。先按“Fn+Q”组合键，使键盘进入可连接状态，此时蓝灯闪烁，然后再进行连接操作。
4. 按“Fn+T”组合键，可使键盘进入OTA模式，此时蓝灯常亮。按Wake Up键可退出OTA模式。

## 指示灯说明
蓝灯闪烁：键盘未连接任何设备，处于可连接状态
红灯常亮：正在充电
绿灯常亮：电已充满

