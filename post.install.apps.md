# Post Intall: _APPS_


## Text Editors:

* FeatherPad: `apt install featherpad`
* GEdit: `apt install gedit`


## IDE:

* VSCode:
 - download: `https://code.visualstudio.com/sha/download?build=stable&os=linux-deb-x64`
 - install: `sudo dpkg -i ./code_1.92.1-1723066302_amd64.deb`
 - requirements: `sudo apt install dirmngr software-properties-common apt-transport-https curl -y && sudo apt-get install -f`

* VSCodium:
  - requires: `sudo apt install dirmngr software-properties-common apt-transport-https curl -y`


### Micro-Controller:

* Arduino:
 - ide: `sudo apt install arduino`
 - additional board manager url: `https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json`
 - update system and boards
 - python related: `sudo apt install pip`
 - pyserial: `sudo python3 -m pip install pyserial`
