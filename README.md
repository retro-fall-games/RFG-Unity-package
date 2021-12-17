# RFG-Unity

RFG Unity Components

## Dependencies

- Everything in manifest.json
- Leantween
- https://github.com/Deadcows/MyBox.git

## Android Debug

```
cd [USER_PATH]\AppData\Local\Android\sdk\platform-tools

.\adb tcpip 5555

.\adb connect 192.168.3.6

.\adb -s 801KPAE1363808 shell -t "logcat"

.\adb -s 192.168.3.6:5555 shell -t "logcat"

.\adb devices
```
