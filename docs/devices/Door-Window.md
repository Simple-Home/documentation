Do you always have to check wheter you have closed the window? Or want to check if the door is open? Smart_Home is here to help! <br>

Reed switches turn on (or off depending on type) when a magnet is nearby. Using them you can easily check if something is in right position (e.g. the door is closed). <br>

By following this Wiki you should be able to check states of these switches from anywhere you want.

***

## First step

In order to use reed switches with Smart_Home, you need to **upload [this](https://github.com/GamerClassN7/Smart_Home/blob/dev/_FIRMWARE/firmwares/ESP01_Basic_DOORWINDOW/ESP01_BASIC_DOORWINDOW/ESP01_BASIC_DOORWINDOW.ino) code to your ESP** (or compatible) board. <br>
Steps in doing this are the same as in [uploading the regular firmware](https://github.com/GamerClassN7/Smart_Home/wiki/Uploading-the-code-to-your-ESP-board).

## Second step

Wire reed switch to your ESP (or compatible) according to this schematic:

<img src="https://github.com/GamerClassN7/Smart_Home/blob/dev/_FIRMWARE/firmwares/ESP01_Basic_DOORWINDOW/Untitled%20Sketch%202_schem.png" height="500" width="500">

***

Or, if you're more familiar with diagrams:

<img src="https://github.com/GamerClassN7/Smart_Home/blob/dev/_FIRMWARE/firmwares/ESP01_Basic_DOORWINDOW/Untitled%20Sketch%202_bb.png" height="620" width="420">

## Third step

If you want, you can place the elements on a PCB. [Here are ready to use gerber files](https://github.com/GamerClassN7/Smart_Home/blob/dev/_FIRMWARE/firmwares/ESP01_Basic_DOORWINDOW/Gerber_PCB_Door_Senzor.zip?raw=true). 

## Fourth step

If you have access to 3D Printer, you can [download gcode here](https://github.com/GamerClassN7/Smart_Home/tree/dev/_FIRMWARE/firmwares/ESP01_Basic_DOORWINDOW/3D_Print_CASE) and print the case.

***

If you need more help with that you can always message us at our [![Discord](https://img.shields.io/discord/604697675430101003.svg?color=Blue&label=Discord&logo=Discord)](https://discord.gg/6BPErAS).

After doing all above steps, you can plug-in your board and open Arduino IDE Serial Monitor to check if everything is working correctly.

**With that all done your board is ready to send data to your Smart_Home web server.** <br>
If you need help with that, read [Creating web server](https://github.com/GamerClassN7/Smart_Home/wiki/Creating-web-server) Wiki.<br>
Good luck on expanding your Smart_Home system!