# c64-cartridge
A C64/C128 basic 8K cartridge.


You can use the schematic to build the pcb or use the ready-made gerber file with standard pcb size for the C64 cartridge.

Required components:
C1 = 100nF ceramic or polyester.
U1 = Eprom 2764 /27C64.
SW1 = 6 mm x 6 mm Tact Switches (optional).

If you use a 27C128 eprom, connect its A13 (pin 26) to ground and use the eprom from address $0000 - $1FFF, or connect it to a switch to select the ROM bank 0-1 with a 10k pull-up resistor.
If you use a 27C256 eprom, connect its A13 (pin 26) to ground and you can use it from the address $4000 - $5FFF, but if you want to use all 4 banks you need to disconnect pin 27 from the positive and use A13-A14 as additional addresses.

EasyEDA project:

https://oshwlab.com/zeus074_5150/simple-8k-cartridge-c64-128
