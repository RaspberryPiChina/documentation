# 设置

树莓派设置向导

## 需要的配件

### 必备品（日常使用）

- [SD卡（TF卡）](../installation/sd-cards.md)
    - 建议使用8G的C4或以上的SD卡，最好已准备好了[NOOBS](../installation/noobs.md)；
- [显示设备和线缆](monitor-connection.md)
    - 一般情况下，支持HDMI或DVI的电视或显示器都可与树莓派一起使用。为保证最佳效果，请使用有HDMI输入的显示设备；另外支持旧式显示设备的接口同样可用。
- 键盘和鼠标
    - 标准的USB键盘和鼠标都适用于树莓派。
    - 已成功配对的无线键盘和鼠标也可使用。
    - 键盘布局设置，请参考[raspi-config](../configuration/raspi-config.md)。
- [电源](../hardware/raspberrypi/power/README.md)
    - 树莓派使用Micro USB接口连接电源（与大多数的移动电话一样）。
    - 电源的最低要求：5V-0.7A；目前
    - Low ampage (~700mA) power supplies will work for basic usage, but are likely to cause the Pi to reboot if it draws too much power.

### Optional

- Ethernet (network) cable [Model B/B+ only]
    - An Ethernet cable is used to connect your Pi to a local network and the internet.
- [USB wireless dongle](../configuration/wireless/README.md)
    - Alternatively, you can connect to a wireless network using a USB wireless dongle, which will require configuration.
- Audio lead
    - Audio can be played through speakers or headphones using a standard 3.5mm jack.
    - Without an HDMI cable, an audio lead is necessary to produce sound.
    - No separate audio lead is necessary if you're using an HDMI cable to connect to a monitor with speakers, as audio can be played directly through the display; but it is possible to connect one if you prefer to have the audio played through other speakers - this requires [configuration](../configuration/audio-config.md).

## Troubleshooting

For any issues during setup, see [troubleshooting](../troubleshooting/README.md).
