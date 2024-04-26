## Chip - Revision 2.0 (2024)

We are working toward a new experimental production run of this board and this folder contains the working files. Our goals will be:

* To pivot away from OrCad in favor of more accessible CAD tools
* Bring current the 2016-era components
* Produce a limited run where we will
    - Update the OS image
    - Integrate a desktop system
    - Introduce an autonomous ideal platform
    - Re-engineer the pin header
    - Render a different use-case for the features

### Results from analysis of current design (1.0)

Since transforming the design from OrCad to Altium, progress has been made to reveal each of the current feature-set, for import into the new production.

* The CPU is an ARM cortex8 R8 chip. It is a mid-range processor for use in deep-embedded, real time systems.
* The power management IC is APX209 which    accepts a battery and outputs several DC outputs.
* The three regulators are LP6226 which produce the 5v, 3.3v and 1.6v.
* The design contains two 40 pin LCDs. The LCDs part numbers are not defined. One of the LCDs is placed at the right side of the board and the other one is placed at the left side. Only the connectors of the LCDs can be seen in the boards.
    - The LCDs should be selected separately or According to the pinouts  of the connectors.
* There is also a remote I2C Bus expander in the design (PCF8574)
    -  In the original product there was a hat that had both banks of 40-pin headers where one could use a VGA or HDMI version to connect to an external monitor.
* There is a Bluetooth IC (8723BS) with an antenna in the board to communicate with  other devices via Bluetooth.
* 