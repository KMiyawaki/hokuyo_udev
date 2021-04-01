# hokuyo_udev

## Install

```shell
$ git clone https://github.com/KMiyawaki/hokuyo_udev.git
$ sudo cp hokuyo_udev/90-hokuyo.rules /etc/udev/rules.d/
```

Reboot PC, connect hokuyo lidar and check device file.

```shell
$ ls -l /dev/sensors/
合計 0
lrwxrwxrwx 1 root root 10  4月  1 16:30 hokuyo_H1106986 -> ../ttyACM1
lrwxrwxrwx 1 root root 10  4月  1 16:19 hokuyo_H1915991 -> ../ttyACM0
```
