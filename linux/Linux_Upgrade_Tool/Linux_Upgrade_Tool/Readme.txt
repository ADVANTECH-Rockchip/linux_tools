v1.28 revision:
1.support to download sparse image and  erase verity info
2.support to erase emmc using erase_lba

v1.3 revision:
1.support gpt download
2.add pl to read partition info from device

v1.31 revision:
1.UL decide to if reset or not after upgrade loader
2.add "rb_check_off"flag in the config.ini.close readback check when set rb_check_off=true

v1.32 revision:
1.DI command add -u -t -re for uboot trust resource
2.DI command chane calling convension of download multi image
3.config.ini place in the $HOME/.config/upgrade_tool/

v1.33 revision:
1.support fixed uuid in the gpt
add one line as following in the parameter:
uuid:partition_name=00000000-0000-0000-0000-000000000000

v1.34 revision:
fix prepare_gpt_backup bug

v1.35 revision:
1.support do operateion on specific device by sn
2.add rid rfi rci rcb of shell mode
3.when not found config.ini in ~./.config/upgrade_tool/,move ./config.ini  

v1.36 revision:
1.fix move file pointer most in the fill chunk of sparse format

v1.37 revision:
1.add EL to erase lba data

v1.38 revision:
1.fix get flash size bug when creating gpt bug

v1.39 revision:
1.support to write sn into vendor
2.optimize progress output

v1.4 revision:
1.destroy gpt when download parameter
2.change timeout of usb transfer to 5s

v1.41 revision:
1. add RL into console mode

v1.42 revision:
1. add release interface into uninitializeUsb

v1.43 revision:
1. judge device by location_id in the wait function

v1.45 revision:
1.location_id support 7 level

v1.46 revision:
1.fix compute last partition size bug during download sparse image 

v1.47 revision:
1.fix parse uuid bug 

v1.48 revision:
1.optimize download progress
2.check size if larger than partition

v1.49 revision:
1.support to switch uvc into rockusb

v1.5 revision
1.add log on download image

v1.51 revision
1.support nor flash erase

v1.52 revision
1.support ubi image download

v1.53 revision
1.support New IDB download

v1.54 revision
1.add gpt command for converting parameter into gpt image

v1.55 revision
1.support to run repeatly

v1.56 revision
1.support to download loader on spi/sfc nand flash(4k page)

v1.57 revision
1.fix download ubi image bug

