# hackintosh

## Reference Guide
* [GitHUb](https://github.com/blacklizard/gigabyte-z390-aorus-pro-wifi-hackintosh-opencore)
* [YouTube](https://www.youtube.com/watch?v=r7mxY9OJVds)
* [ProperTree](https://github.com/corpnewt/ProperTree)


## Hardware


| Part Type     | Name          | 
| ------------- |:-------------|
| CPU    | [Intel Core i9-9900K](https://www.amazon.com.au/gp/offer-listing/B005404P9I/ref=dp_olp_unknown_mbc)  |
| Mother Board      | [Gigabyte Z390 AORUS PRO WiFi ](https://www.amazon.com.au/GIGABYTE-Z390-AORUS-PRO-Motherboard/dp/B07HRZKPXM/ref=sr_1_1?dchild=1&keywords=Gigabyte+Z390+AORUS+PRO+WIFI+ATX+LGA1151+Motherboard&qid=1598263008&s=computers&sr=1-1)|
| GPU | [Sapphire 11265-67-20G Radeon Pulse RX 580](https://www.amazon.com.au/gp/product/B083W2JP4W/ref=ox_sc_act_title_1?smid=A4XRJ8S0WXSO0&psc=1) |
|RAM| [Crucial Ballistix Sport LT 3200 MHz DDR4 DRAM (Red)](https://www.amazon.com.au/Ballistix-Sport-PC4-19200-288-Pin-16GBx2/dp/B07MNJNSQ9/ref=sr_1_3?dchild=1&keywords=Crucial%2BBallistix%2BSport%2BLT&qid=1598262737&sr=8-3&th=1)|
|Wifi Card| [BCM4360 AC1200](https://www.amazon.com.au/gp/product/B07T9JD93Y/ref=ppx_yo_dt_b_asin_title_o03_s00?ie=UTF8&psc=1)|



## MountEFI
* EIF is by default hidden need to show 
Use [MountEFI](https://github.com/corpnewt/MountEFI), to mount the EFI drive of the bootable usb

## Find the Kexts

## ACPI
* use the [SSDTTime](https://github.com/corpnewt/SSDTTime) to dump 
* or use the prebuild SSDTTime file
* Manually build 



## config.plist
* Use [ProperTree](https://github.com/corpnewt/ProperTree)) to configure the config.plist according to this [guide](https://dortania.github.io/OpenCore-Install-Guide/config.plist/coffee-lake.html#misc)


## BIOS Conifg
### CFG Lock
* [GitHub Guid BIOS Section](https://github.com/blacklizard/gigabyte-z390-aorus-pro-wifi-hackintosh-opencore/blob/master/BIOS.md)
* [Fix your BIOS CFG Lock - Youtube](https://www.youtube.com/watch?v=W4JXVNJsK98)
* [Z390 AORUS PRO WIFI ](https://www.gigabyte.com/Motherboard/Z390-AORUS-PRO-WIFI-rev-10/support#support-dl-bios)


| Firmware Version	    | Command          | 
| ------------- |:-------------|
|F9, F10, F11 & F12c/j| setup_var 0x5C1 0x00|


## Possible Trouble Shooting
* use the SSDT from the Github Guide , since that probabily would get SSDT complied from that mother board
* use the target windows and SSDT time to produce the SSDT files
* Need to know the firmware version for the CFG unlock
* Ktext double check
* BIOS settings





