1. ```cd esp-idf-example/tcp```
2. ```idf.py set-target esp32s2```
3. ```idf.py menuconfig```
    * Example Connection Configuration
        * setting Wi-Fi SSID/PWD
        * disable IPv6

    * Component config → ESP System Settings → Channel for console output → USB CDC
4. ```idf.py build```
5. ```idf.py -p (PORT) flash```