Gen1 binaries
=============

The most important files are marked with **bold**.

HW-related binaries
-------------------

* **boot.bin** (bootable flash image)
* **parallella.bit.bin** (u-boot loadable bitstream)

SW binaries
-----------

* fsbl.elf (First Stage Boot Loader, included in boot.bin)
* uboot.elf (U-Boot image, included in boot.bin)
* **uImage** (Linux kernel image)
* devicetree.dts (device tree source)
* **devicetree.dtb** (compiled device tree)

Misc
----

* stub.tcl (tcl script for putting the CPU in debug mode)
* ps7_init.tcl (FSBL settings as tcl script for JTAG operation)
