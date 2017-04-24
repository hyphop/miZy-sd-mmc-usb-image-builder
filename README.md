# ABOUT miZy\_sd\_mmc\_usb\_image\_builder

SD/MMC/USB firmware image builder (for sunxi Orange Pi Zero, another sunxi boards maybe work too )

Its just a part or miZy project, and same as other our parts can standalone used

This perl script no need any libs or another deps

# USAGE

help

    ./miZy_sd_mmc_usb_image_builder --help

common usage for 8M image, output to firmwares/orange\_pi\_zero\_hyphop\_mizy\_sd\_mmc\_usb\_demo-8M.bin

    ./miZy_sd_mmc_usb_image_builder

    or 

    size=16M ./miZy_sd_mmc_usb_image_builder

custom config

    ./miZy_spi_image_builder miZy-custom.conf

# CONFIG FILE

default config

    miZy_sd_mmc_usb_image_builder.conf

config file its a same pure perl code!

# PATHS

put your files (uboot scripts env fex/dtc kernel squashfs initramfs userdata) in @SCAN\_PATH dirs
by default are

    .
    ./bin
    ./bin.local

# WRITE IMAGE EXAMPLE

write to SD card 

    ./tools/img2sd firmwares/orange_pi_zero_hyphop_mizy_sd_mmc_usb_demo-8M.bin yes

or write to USB 

    ./tools/img2usb firmwares/orange_pi_zero_hyphop_mizy_sd_mmc_usb_demo-8M.bin yes

# miZy

tiny fast embedded linux, for sunxi Orange Pi Zero (and maybe other boards) and mods.
Now under active development, but is usable already )

# LINKS

- [https://hyphop.github.io/mizy/](https://hyphop.github.io/mizy/)
- [https://github.com/hyphop/miZy-sd-mmc-usb-image-builder](https://github.com/hyphop/miZy-sd-mmc-usb-image-builder)
- [https://github.com/hyphop/miZy-spi-image-builder](https://github.com/hyphop/miZy-spi-image-builder)
- [https://github.com/hyphop/miZy-uboot](https://github.com/hyphop/miZy-uboot)
- [https://github.com/hyphop/miZy-linux-kernel](https://github.com/hyphop/miZy-linux-kernel)
