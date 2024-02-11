# aiventure-computer

The computer that runs our huggable, henry, and fred products. David is being considered as a second-generation model as the bipedal robot is much more sophisticated and needs more thought on how the hardware would manage this and the presence of _ideal_.

## The target

* The target OS for the new design is <a href="https://debian.org" target="_blank">Debian 12</a> with Linux kernel <a href="https://cdn.kernel.org/pub/linux/kernel/v5.x/linux-5.10.182.tar.xz" target="_blank">5.10.182</a>. We have the option as well to keep it in the version 4.4.13 kernel according to `b149`. This would be the path of least-resistance. This version is a moving target and is subject to change in the future.
* The entire board will have to be proofed in order to obtain a rather assured estimate of the costs-per-unit of manufacture. There are anticipated issues with finding replacement parts. There is a question of upgrading. The focus is only on the main board.

## The source
The _project_ directory contains the correct <a href="http://www.orcad.com/" target="_blank">OrCAD</a> file. However, it seems to be missing footprints. They are found as a *.lbr file, which is for <a href="https://www.autodesk.com/products/eagle/free-download" target="_blank">Eagle</a>.

In the historic version, there was no linkage between the design files meaning the entire project needed to be rebuilt in OrCad.

The milestone is to understand the current status and what needs to be done to prepare it for manufacturing. Of course, clean-up some of the more silly aspects of the design and improve the quality of component choices.