# aiventure-computer

The computer that currently runs our portable robotics projects. As finding a replacement has been problematic, can we take ownership of this board?

## The target

* The target OS for the new design is Debian 12 (bookworm) with Linux kernel 6.6.23. The last kernel for the old board is version 4.4.13 according to `b149`. 
* The entire board will have to be proofed in order to obtain a rather assured estimate of the costs-per-unit of manufacture. There are anticipated issues with finding replacement parts. There is a question of upgrading. The focus is only on the main board.

## The source

* The _project_ directory contains the correct <a href="http://www.orcad.com/" target="_blank">OrCAD</a> file. However, it seems to be missing footprints. They are found as a *.lbr file, which is for <a href="https://www.autodesk.com/products/eagle/free-download" target="_blank">Eagle</a>.
* It needs to be understood if the file can be opened in Altium and rendered accordingly, or if we need to purchase a license for OrCad.
* The milestone is to understand the current status and what needs to be done to prepare it for manufacturing. 

## What needs to be accomplished

This board needs to be put into production to support [emotional](https://emotional.toys) toys products. The following changes need to be considered so that this board is brought-up to the current (2024) technological standards.

* CPU/GPU
* RAM (SDRAM) - 16 GB
* NVRAM (eMMC) - 256 GB
* Pin interfaces at board level (no headers) (Requirement)
* Recharable point for JST connected battery (Requirement)
* USB should be USB-C (Requirement)

I will add to this list as the specifics are investigated.