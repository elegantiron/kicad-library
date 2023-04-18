# KiCad Library

A collection of symbols and footprints for various devices.

I got *really* tired of importing footrpints that would then fail KiCad's DRC because of overlapping lines or discrepancy in pad naming.

On top of that, some of the symbols that I've found out in the wild have pin names that don't quite line up with manufacturer's datasheet. I also like to have alternate pin functions defined in the symbols to better use the ERC. Finally, I like to be able to just pull the proper model number out of the symbol library instead of having to worry about grabbing the generic one that has the right pin-out.

# Installation
Copy the library you want to a folder on your computer. Then, use the KiCad library managers to add them. If you add the footprint library first, then the symbol should properly associate without any errors.

# Available Devices
Here's a list of symbols and footprints that are available in the library. Items in *italics* have associated footprints that you will probably want. If a part uses a standardard footprint, then I've just associated it with the generic one KiCad ships with.

## Symbols
* Espressif
  * *ESP32-C3-WROOM-02*
* Rohm
  * RUC002N05

## Footprints
* Espressif
  * ESP32-C3-WROOM-02