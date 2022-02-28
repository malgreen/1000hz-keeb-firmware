# 1000hz-keeb-firmware
Firmware for various keyboards/PCBs supporting both 1000hz refresh rate and VIA configurator

*[QMK Toolbox](https://github.com/qmk/qmk_toolbox) required*
#
### Supported keyboards
- BM65 ISO

#
### How-to
  - Open QMK toolbox
  - Put keyboard in DFU mode by (different for each keyboard, can commonly be found on the keyboard/PCB product page)
  - Load the .hex file for the keyboard included with this download
  - Flash
  - Done, close QMK toolbox

#### Optional
If a .json file for the keyboard is included in this download, it needs to be loaded in VIA each time it is configured:
  - Open VIA
  - Click on design tab
  - Load the .json included with this download
  - Configure your keyboard
