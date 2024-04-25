## aiventure-computer

The computer that currently runs our robotics platforms. As finding a replacement has been problematic for new development, can we evolve the design toward a manifestation of an aeon-class machine?

_Project Goals_

This board needs to be put into production to support [emotional](https://emotional.toys) toys products. The following changes need to be considered so that this board is brought-up to the current (2024) technological standards.

* CPU/GPU - Eight cores
* RAM (SDRAM) - 16 to 48 GB
* NVRAM (eMMC) - 250 to 500 GB
* Pin interfaces at board level (male headers) (Requirement)
* Rechargable feature for JST connected battery retained but which allows higher-capacity batteries (Requirement)
* USB should be USB-C (Requirement) 
* Design in an open source toolset 

The above list is fluid as its specifics will change as the investigation ensues.

## The target

* The target OS for the new design is Debian 12 (bookworm) with Linux kernel 6.6.23. The last kernel for the old board is version 4.4.13 according to `b149`. 
* The entire board will have to be proofed in order to obtain a rather assured estimate of the costs-per-unit of manufacture.

## The source

* The _project_ directory contains the correct <a href="http://www.orcad.com/" target="_blank">OrCAD</a> file. However, it seems to be missing footprints. They are found as a *.lbr file, which is for <a href="https://www.autodesk.com/products/eagle/free-download" target="_blank">Eagle</a>.
* It needs to be understood if the file can be opened in Altium and revised that a developer can use KiCad or EasyEDA.
* The milestone is to understand the current status and what needs to be done to prepare it for manufacturing of 500 units planned. 
