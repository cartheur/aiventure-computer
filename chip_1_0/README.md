## CHIP v1.0 Feature-Set

Features implemented on this model:

* Built-in Wi-Fi 802.11b/g/n, Bluetooth 4.0
* One USB host with type-A receptacle, one USB On-The-Go port
* Composite video and stereo audio port via mini TRRS
* Optional composite TRRS to RCA audio-video cable
* Optional VGA adapter and HDMI adapter (see Hardware extensions below)
* Open source hardware and open source software
* Unfortunately, the OrCad is _not_ open source
* Up to 45 GPIO ports
* Supports 1-Wire and I2C protocols, PWM output
* Serial console and Ethernet via USB for quick headless operation
* Power options include 5V via USB OTG, 5V via CHN pin, and by 3.7V battery
* Onboard NAND storage, 4-8 GB, pre-installed Linux OS (Debian)
* API-based firmware update
* The board is 60mm × 40mm x 15mm in size.
* The total addressable memory for the Cortex-R8 processor is 4GB.

_Analysis results_

* The schematic illustrated a number of errors which needed to be fixed. There are a multiple of errors in the pcb.
* The solution is to produce this board without any changes, but with the bugs sorted. After a round of manufacturing and software installation, resolve newly appearing bugs as a part of development of the second version that contains the updated requirements.

### Strategic initiatives

* To streamline the design process, the first version of the board is designed with Cortex-R8 and after implementing and manufacturing this version of project, increment the design to the Cortex-R82 in the second version.