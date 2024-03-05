# Kolbe Customs Controller

This project is a remix of the Flatbox rev5 by jfedor2 here: https://github.com/jfedor2/flatbox/tree/master/hardware-rev5. The changes made are the following:

- Shadow lines to make a cleaner seam
- Use of M3 heat inserts
- Compatibility with Choc v2 switches

This project requires the following:

- [3D printed](3d-models) top and bottom case, 11 24mm buttons, and 1 or 2 30mm buttons
- The [PCB](pcb), with or without the USB passthrough assembely
- [RP2040-Zero](https://www.waveshare.com/rp2040-zero.htm)
- 6x [6x6x5mm tactile switches](https://www.amazon.com/gp/product/B01CGMP9GY/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1) (these come on the PCB if you buy it preassembled via jlpcb)
- Optional [USB port](https://www.mouser.com/ProductDetail/640-USB1046GF0190LBA) if using USB passthrough for Xbox S|X or PS5
- 12 or 13 [Kailh low profile (choc v2) switches](https://mechanicalkeyboards.com/shop/index.php?l=product_detail&p=6341) of your choice
- 12 or 13 [Kailh low profile hotswap sockets](https://mechanicalkeyboards.com/shop/index.php?l=product_detail&p=6995)
- 7x [M3 3.8mm heat set inserts](https://www.mcmaster.com/94180A331)
- 7x [M3 8mm Screws](https://www.mcmaster.com/91294A128) and wrench
- \(Optional)Right angle USB-C cable

Included in the 3D Models folder, there are 4 case tops. You will choose the coresponding top for if you want 2 thumb buttons, USB passthrough, or both. All options use the same bottom case.

I print my cases and buttons 0.3mm layer height with a 0.6mm nozzle.

To flash the firmware, connect the board to a computer with a USB cable, then press the RESET button while holding the BOOT button on the RP2040-Zero. A drive named "RPI-RP2" should appear. Copy the UF2 file you downloaded to that drive.

PCB design licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

PCB design uses the following:

- [remix of jfedor2's flatbox rev5](https://github.com/jfedor2/flatbox/tree/master/hardware-rev5)
- [keyswitches.pretty](https://github.com/daprice/keyswitches.pretty) by [daprice](https://github.com/daprice) ([CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/))
- RP2040-Zero STEP file downloaded from [Waveshare wiki](https://www.waveshare.com/wiki/RP2040-Zero)
