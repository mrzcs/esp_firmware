# esp_firmware

esptool.py --chip esp32s3 --port /dev/ttyACM0 --baud 921600 erase_flash

esptool.py --chip esp32s3 --port /dev/ttyACM0 --baud 921600 write_flash -z 0x0000 xxxx.bin

## MPY: esp32s3_N16R8_v1.19.1.bin
## LVGL+MPY: esp32s3_N16R8_lvgl_v1.19.1.bin
