Libs:
- TJpg_Decoder
- TFT_eSPI
- U8g2_for_TFT_eSPI

Arduino IDE Board Type: ESP32dev


Den /jpg/ Ordner auf eine FAT32-Karte draufkopieren und für WLAN wifisetup.h editieren.



Installation of ESP32:
wget https://raw.githubusercontent.com/ojaksch/tty2tft/main/installer.sh -O - | bash -s -- IDENTIFY

Update of ESP32:
wget https://raw.githubusercontent.com/ojaksch/tty2tft/main/installer.sh -O - | bash

Installation of MiSTer software:
wget https://raw.githubusercontent.com/ojaksch/tty2tft/main/update_tty2tft.sh -O - | bash
