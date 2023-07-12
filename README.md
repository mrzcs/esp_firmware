# esp_firmware

esptool.py --chip esp32s3 --port /dev/ttyACM0 --baud 921600 erase_flash

esptool.py --chip esp32s3 --port /dev/ttyACM0 --baud 921600 write_flash -z 0x0000 xxxx.bin

## MPY for esp32s3 devkit v1: esp32s3_N16R8_v1.19.1.bin
## LVGL+MPY for esp32s3 devkit v1: esp32s3_N16R8_lvgl_v1.19.1.bin
## LVGL+MPY for esp32 devkit v1: esp32_lv_micropython.v1.19.1-ili9341-xpt2046.bin
