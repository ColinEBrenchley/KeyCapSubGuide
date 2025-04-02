# Custom Keycap Build Guide

## Required parts

Part name | Quantity | Remarks | Photo |
| ------- | -------- | ------- | ----- |
| PBT Keycaps | 
| Heating element | 
| Clamp | 
| Dye Sub Prints | 


## Introduction
This document is intended to be a culmination of the information gathered around the process of Sublimination dyeing custom legends of PBT keycaps. Getting it right can take some trial and error but hopefully with this guide, some of the pain points can be avoided. 


Mark the surface with masking tape to make it easy to keep track of the back and front of each board.
![51965707-c6841d80-24ad-11e9-8e00-b7113b20fb67](https://user-images.githubusercontent.com/6285554/51967194-0947f480-24b2-11e9-860f-e45197cf0983.jpg)
![unadjustednonraw_thumb_2ccb](https://user-images.githubusercontent.com/6285554/53638905-1d2a7600-3c6b-11e9-9a39-a121c9b407b6.jpg)


## Creating the Legends
Utilizing the blank keycap template (forked from this video: ) open it in some sort of vector graphics software, such as Adobe Illustrator, Inkscape, CorelDRAW, etc. Starting with the Alphas, choose the font for the keycaps and size them according to your desired legend size. If a sub-alpha is also wanted, choose that font and add those as well. 

//Post an video portion going over the alpha and sub-alpha creation.

When it comes to icons and logos there are a couple of ways to approach this. 
1. Design and draw the logos yourself. 
2. Utilize an image tracing software and find pictures of it online. (If you are using other people's art do not create commercially).
3. Trace your own vectors based on other images. 

 // Post a video of these options. 

For more complicated 


## Solder the sockets
The sockets are mounted on the **back side**, the same side as the diodes.

Much like the approach used for the diodes above, begin by pre-soldering one side of the socket pad, place the component, and hold it in place with tweezers. (The sockets can also be held in place by hand, but please take extra care not to burn yourself.)
The image shows a soldered MX socket; please install Choc socket on the lower side.
![socket](https://user-images.githubusercontent.com/6285554/57197682-3de1b580-6fa5-11e9-90b1-fca894e1e7d2.png)

For parts that require force, firmly solder both pads and check the final result for any looseness/wiggling.
![2019-01-26 14 38 04](https://user-images.githubusercontent.com/6285554/51967230-2250a580-24b2-11e9-94ce-591746c49f50.jpg)


## Soldering the TRRS jack and reset switch
The TRRS jack and the reset switch are mounted on the **front side** (the one with the sticker on the mark).
Attach the parts and fix them temporarily with masking tape. Turn over the board and solder the pins, making sure that the TRRS jack and reset switch are in firm contact with the board.
![2019-01-26 14 39 53](https://user-images.githubusercontent.com/6285554/51967627-2c26d880-24b3-11e9-9764-aa51975c1eef.jpg)
![2019-01-26 14 43 23](https://user-images.githubusercontent.com/6285554/51967628-2cbf6f00-24b3-11e9-96e6-8f003c53d57b.jpg)


## Attach the OLED display
On the **front side** of the board, apply enough solder to bridge the four jumper terminals in the ProMicro section.
Attach the connector for the OLED, much like the TRRS jack above. Be careful to avoid adding a lot of solder, as it is easy for solder to flow into the connector.
![unadjustednonraw_thumb_2db2](https://user-images.githubusercontent.com/6285554/53293031-d45c6280-380f-11e9-8f1c-1c167b27cfd3.jpg)

Insert the OLED pin into the socket, attach the OLED module to it, and solder the four pins.


## Install Pro Micro
The pin header enclosed in the bag of ProMicro is not used. For kits purchased at YushaKobo, a spring pin header is included, so use that.
![IMG_2662](https://user-images.githubusercontent.com/6285554/57210525-f5171480-7017-11e9-9d92-3a345d53db94.jpg)
When attaching with a spring pin header (con-through), solder it according to the method described in the Helix build guide and then attach it to the Lily 58 PCB. [Helix build guide](https://github.com/MakotoKurauchi/helix/blob/master/Doc/buildguide_en.md#pro-micro)

Note the **outlined sets of holes in PCB,** and insert the ProMicro into the outlined holes. Please be careful, as the **connections are different for the right and left boards.**

![ProMicro_PCB](https://user-images.githubusercontent.com/6285554/48819671-6a599a80-ed94-11e8-8e5d-6a6abca326a7.png)


## Attach the spacer
Attach four 10mm round spacers to the holes near ProMicro.
It's easy to insert a screw from the back of the board and attach the spacer from the top.
![2019-01-26 15 02 38](https://user-images.githubusercontent.com/6285554/51967859-c0913b00-24b3-11e9-966c-f3621ed398e5.jpg)

Peel off the masking tape used to identify the front and back of the board.

## Attach the key switch
Attach the top plate spacers for alignment. (MX: 7mm Choc: 4mm)
![2019-01-26 14 56 05](https://user-images.githubusercontent.com/6285554/51967395-912dfe80-24b2-11e9-9cc7-b4520063f36c.jpg)
![2019-01-26 14 56 24](https://user-images.githubusercontent.com/6285554/51967376-83787900-24b2-11e9-82a0-850556daccfc.jpg)

Attach four key switches to the top plate. (In the case of Choc switches, starting with two switches in the plate may be easier.)
![2019-01-26 14 58 48](https://user-images.githubusercontent.com/6285554/51967380-87a49680-24b2-11e9-80b9-a45564afc8cf.jpg)
  
Insert the switch into the board for alignment, and line up the components.
![2019-01-26 15 01 12](https://user-images.githubusercontent.com/6285554/51967478-c3d7f700-24b2-11e9-9f2f-4e75efc215a1.jpg)


After confirming that there are no bends in the switch pins, you can attach it firmly by starting from the middle row and working outward.
Be careful: KailhBOX switches and Choc switches require some power for installation.
After mounting the plate, push the switches again to make sure that installation is complete.
![2019-01-26 15 10 06](https://user-images.githubusercontent.com/6285554/51967840-b66f3c80-24b3-11e9-8f50-6d8d31fe85e5.jpg)

## ProMicro protective acrylic installation
Peel off the protective plastic layer covering the acrylic, and attach the acrylic to the board.
**Mount with the wider side (labeled "幅が広い" here) outwards.** 

![Attach with screws](https://user-images.githubusercontent.com/6285554/48837829-c4288780-edc9-11e8-8efb-6714d8e68e92.png).

![2019-01-26 15 21 15](https://user-images.githubusercontent.com/6285554/51967842-b8d19680-24b3-11e9-8402-85180ce10403.jpg)

## Write key map
The board requires a keymap in order to function. This section assumes that you're familiar with keymaps and the use of the QMK tool. If not, please refer to [the QMK "Getting Started" guide](https://docs.qmk.fm/#/getting_started_build_tools) (Windows: MSYS2; Mac, Linux: avrdude)

The [QMK Toolbox](https://github.com/qmk/qmk_toolbox/releases) can be used to write non-customized keymaps via a GUI, avoiding the need to configure a local QMK environment. (For custom keymaps, it's recommended to build the full environment described above).

 
Execute the following in the `qmk_firmware` directory to write the default Lily58 keymap

    sudo make lily58:default:avrdude


When **`Detecting USB port, reset your controller now ...`** is displayed, press the reset button on the keyboard to start writing.
Each half of the keyboard must be programmed separately using this approach.


## Default keymap
The default keymap is laid out on the assumption that it will be used in the MacOS/US keyboard environment. Feel free to get creative and experiment with keymaps that match your preferences; consider changing to the JIS layout or adding a key to switch between English and Kana, for example.

The best of my own keyboard:
![lily58_default](https://user-images.githubusercontent.com/6285554/47273241-38ee8300-d5cc-11e8-9099-10c1b35e24fc.png)

## Operation check
Connect the left and right sides with a TRRS cable, connect the MicroUSB cable to ProMicro on the left side (in the case of the default key map), and check if the key responds.
The build is completed by attaching the four rubber feet to the back of each board. Thank you for your hard work.
![2019-01-26 15 24 52](https://user-images.githubusercontent.com/6285554/51967992-24b3ff00-24b4-11e9-8cd3-1e679094682f.jpg)
![unadjustednonraw_thumb_2ddc](https://user-images.githubusercontent.com/6285554/53640050-6203dc00-3c6e-11e9-9434-5591ed3e414f.jpg)


## When in trouble
### Q. One or more rows/columns of key switches do not respond
A. The ProMicro board may not be soldered and attached firmly. Check again, and re-solder and reinstall if necessary.

### Q. A single key switch doesn't respond 
A. There may be a problem with the key switch's insertion, socket or diode soldering.

In the case of bad key switch insertion:
After removing the key switch, make sure that the pins aren't bent, and then push it in again and install it.

In the case of badly attached socket:
Re-solder the problem socket, or reflow and add solder if the joint is weak.
  
In the case of badly attached diode:
Check the direction of the diode in question. If it is wrong, remove it and re-solder it. Additionally, if there isn't enough solder, please re-solder.

### Q. A symbol different from the symbol input by "@" or "[" etc. is input (on Windows, etc.)
Since recognition of keyboard is recognized as JIS keyboard on OS, another symbol will be input when inputting with Lily 58 (treated as US keyboard).
Please set Lily 58 as a US keyboard in the OS keyboard settings. After switching, switching to Japanese input becomes the switching key for the US keyboard, and it differs from the JIS keyboard, so please be careful (it can be customized with the key map etc.).


**If you have any problems, please feel free to send a message to the "#Lily58" channel on Discord ("Self-Made Keyboards in Japan" (https://discordapp.com/invite/NM7XtDW)) or Twitter: @F_YUUCHI**

## Change the key map
This self-made keyboard use the QMK firmware, described above. The QMK firmware is highly customizable, and you can unlock a lot functionality simply by editing the key map.
### Edit keymap.c and customize
When customizing a keymap, start by making a copy of the `qmk_firmware/keyboards/lily58/keymaps/default` folder and modifying that directory's internal `keymap.c` file.
Please refer to the [official QMK documentation](https://docs.qmk.fm/#/keycodes) for the key codes and programming specifics.

After changing the key map,

    sudo make lily58:(any folder name):avrdude

If you get an error, please double-check the board, connection and command.
  
### How to customize using QMK Configurator (deprecated)
If you use [QMK Configurator](https://config.qmk.fm/#/lily58/rev1/LAYOUT), you can create an original keymap on the browser without editing the `keymap.c` file.
Load the downloaded JSON file into the QMK Toolbox and write it to the boards.  