# Beechat Clip
## _The smatphone gateway to the Beechat Network_

![BNSLTD](https://beechat.network/wp-content/uploads/2021/02/powered-by-1.png)

General
-------------------

This product is a plug-and-play RF module that operates with the Digi XBee SMT line. This unit works with all XBee SMT Pad modules, standard and Pro version. For demonstration purposes the repo uses the XB8X-DMUS-001 in the 863-870 MHz range module. Design consists of the XBee® SX 868 module and USB-to-UART converter that allows users to simply plug the module into their smartphone over USB-C cable.

Additional on-board LED indication for TX/RX data, RSSI level and power (5V). Reset tactile button allows rebooting the RF module when needed.  

Repository Contents
-------------------

* **/Hardware** - All Eagle design files (.brd, .sch)
* **/Production** - Test bed files and production panel files

Image
-------------------
![image](https://github.com/BeechatNetworkSystemsLtd/Beechat-Clip/raw/main/beechat-clip.jpg)

Features
-------------------

* **Dimensions:** 26 x 53 mm
* **USB - UART bridge:** FT231XQ
* **RF module:** XB8X-DMUS-001
* **Input voltage:** 5V (USB)
* **Logic of UART signal:** 3.3V

Repository Contents
-------------------

/OUT_Beechat_REV1.0:
    • /Step 1 - PCB Manufacturing  (Gerber files, NC Drill, PCB specs)
    • /Step 2 - Board Assembly (Pick & Place, Assembly drawing, 3DPDF, BOM)
    • /Step 3 - 3D (3DPDF, STEP 3D)
    • /Step 4 - Schematic (PDF schematic)
    • /Step 5 - Source Files (source design in Altium Designer)

Product Versions
-------------------

REV1.0 - first design revision


License Information
-------------------
The hardware is released under [Creative Commons ShareAlike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/).

Distributed as-is; no warranty is given.

