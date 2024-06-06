# CH32V203-USBCDC

CH32V203のUSBD機能を使ったUSB-CDCライブラリ。PlatformIOやArduino IDEで利用可能。

USB-CDCを使う場合、システムのクロック周波数は以下のものに限られるので注意（HSI, HSEのいずれも可）
* 48MHz, 96MHz, 144MHz

`#include <usb_serial.h>`と記述することでSerialをUSBSシリアルとして使うことができるようになる。

-------------------

USB-CDC library with the USBD functionality of the CH32V203. This is available for PlatformIO and Arduino IDE.

Note that when using USB-CDC, the system clock frequency is limited to the following (both HSI and HSE are OK)
* 48MHz, 96MHz, 144MHz

Serial can be used as USBS serial by writing `#include <usb_serial.h>`.
