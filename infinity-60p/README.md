Firmware for my Infinity 60% keyboard
=====================================

From the Input Club's configurator ([github][gh], [web][ic]). This repository
contains the following layout:

![][ss]

[ic]:https://input.club/configurator-md-1-1-alphabet/
[gh]:https://github.com/kiibohd/KiiConf
[ss]:./layout.png

Notice the lack of a flash key -- this is because the model of infinity I am
using has a physical flash button on the back.

### Installation

+ Plug in your keyboard
+ Install `dfu-util` (if you don't have it already)
+ Press the flash button
+ Check `dfu-util --list` to make sure you can see your keyboard
+ Flash with `dfu-util --download ./kiibohd.dfu.bin` (assuming you are in this
  directory).
+ Your keyboard is ready to go!

