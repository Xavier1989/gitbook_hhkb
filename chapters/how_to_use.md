# 使用说明
## 连接
### 蓝牙连接
当控制板接上电池后，蓝色LED灯开始闪烁。表示控制板开始工作，等待蓝牙设备进行连接。接下来，以macOS平台演示如何连接。

1.首先打开蓝牙偏好设置，可以看到名字以“HHKB”开头的键盘设备，这就是我们的键盘。
![bluetooth_config](../images/bluetooth_config.png)

2.点击连接，等待其连接完成，显示已连接。
接下来，按一下command+tab键，若可以进行任务切换，说明键盘可以使用了。

### USB连接
默认情况下，当USB未连接时，键盘通过蓝牙输入。当插入USB后，键盘自动切换到USB输入。拔掉USB，自动切换到蓝牙输入。

### 输入接口切换
按下“Fn+U”组合键（U为USB的首字母），手动切换到USB输入。
按下“Fn+B”组合键（B为Bluetooth的首字母），手动切换到蓝牙输入。

## 其它功能说明
1. 连续30分钟无按键操作，键盘将主动断开连接并进入待机状态。也可以通过按“Fn+R_Alt+S“组合键手动进入待机状态。此时耗电量极低，可忽略不计。
2. 待机状态下，键盘不能使用。通过按侧面的Wake Up键可唤醒键盘以继续工作，此时会自动连接到之前的设备。
3. 按“Fn+T”组合键，可使键盘进入OTA模式，此时蓝灯常亮。按Wake Up键可退出OTA模式。
4. 键盘侧面的Wake Up按键为硬件复位功能。当键盘出现异常时，可通过此键重启键盘。

## 指示灯说明
红、绿、蓝三色LED，用于指示键盘的工作状态。

 LED|ON|OFF|BLINK
 :--:|:--:|:--:|:--:
 RED|充电中|/|低电量
 GREEN|电充满|/|/
 BLUE|/|/|蓝牙未连接

