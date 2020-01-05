# m5stack-freertos-shadow
Amazon FreeRTOS Shadow demo for M5Stack

Get current time from ntp.nict.go.jp by HTTP protocol.

Require ESP-IDF development environment.



### Run

Check out this repo.

```
git clone https://github.com/fukuen/m5stack-freertos-shadow --recursive
```

Set or copy Wi-Fi infos.


Build (Windows example)

```
cmake -DCMAKE_TOOLCHAIN_FILE=amazon-freertos/tools/cmake/toolchains/xtensa-esp32.cmake -GNinja -S . -B build
cd build
ninja
```

Flash and monitor

```
idf.py flash monitor
```

