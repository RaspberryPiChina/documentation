# 设置

树莓派设置向导

## 需要的配件

### 必备配件（日常使用）

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
    - 电源的最低要求：5V-0.7A；对于目前最新版本树莓派2代B型，建议使用5V-2A的稳压电源。
    - 低功率（电流低于700mA）电源也可能提供基本运行所需的电源，但一旦供电不足时，树莓派可能会因此而重启。

### 可供选择的配件

- 网线[针对B/B+/2B]
    - 接入局域网或直接接入互联网。
- [USB无线网卡](../configuration/wireless/README.md)
    - 或者选择无线网卡接入局域网，需另行配置无线局域网。
- 音频线
    - 3.5mm的音频线连通音箱或耳机后即可播放音频。
    - 若不使用HDMI线，需连接音频线方可播放音频。
    - 若已使用HDMI线连接上带有音箱的显示器，则毋须另接音频线，显示器的音箱即可播放音频；此时如需使用其他音箱播放音频，则需另接音频线，请浏览[配置方法](../configuration/audio-config.md).

## 故障处理

若在设置过程中遇到任何问题，请参考[故障处理](../troubleshooting/README.md).
