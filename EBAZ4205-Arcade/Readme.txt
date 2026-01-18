EBAZ-4205 Arcade PCB for the EBAZ-4205 ZYNQ 7010 FPGA Bitcoin Miner control Board. Pinballwiz.org 2026

Notes:
Only use a suitable 5V Max DC Power Supply as this is required to supply power to the EBAZ4205 and PS2 Keyboard.
Consult the documents contained in the Docs Folder for information regarding construction and schematics.
When using the EBAZ-4205 Arcade PCB ensure that the EBAZ4205_Arcade.xdc Constraints File is included in the Vivado project.

Build:
* Obtain EBAZ-4205 Arcade PCB design gerber files zip archive (ebaz_arcade_v##.zip) and upload to jlcpcb.com for manufacturing.
* Obtain parts specified in the EBAZ-4205 Arcade PCB documentation from aliexpress.com or similar supplier.
* Construct EBAZ-4205 Arcade PCB and connect a VGA Monitor, PS2 Keyboard and Stereo Speakers.
* Open an Arcade project file using Vivado (version 2022.2 is recommended).
* Compile the arcade project updating filepaths to source files as necessary.
* Connect to EBAZ-4205 Board JTAG header and program EBAZ-4205 FPGA Board.


