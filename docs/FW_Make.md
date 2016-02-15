
# WICED Firmware Compilation Guide

This guide provides information for compiling WICED application firmware and loading firmware using the bootloader DFU mode through the onboard USB or the RBLink.


## Firmware Compilation

Start a command line tool, e.g. Command Prompt (Windows) or Terminal (OSX and Linux). Navigate to the WICED SDK root folder.

The following commands use the snip.scan project as an example.

For OSX & Linux:
	
	$ ./make rbl.rgb-RB_DUO

For Windows:
	
	C:\WICED-SDK-3.3.1> make rbl.rgb-RB_DUO

After that, in the 'build/rbl_rgb-RB_DUO/binary' folder, there are two files compiled 'rbl_rgb-RB_DUO.bin' and 'rbl_rgb-RB_DUO.bin_MSD.bin'. The first one is for uploading using DFU mode while the second one is for using the RBLink drag and drop method.


## Uploading Firmware

There are three methods for uploading WICED application firmware for the Duo:

* Bootloader DFU Mode
* RBLink
	* OpenOCD (official WICED SDK method)
	* Drag & Drop


## Bootloader DFU Mode

* see [this](../firmware/DFU/README.md) document for details.


## RBLink

* See [this](../firmware/RBLink/README.md) document for details.


