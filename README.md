# Mini-Port-Replicator-PA2703U-VGA-Keyboard-Mouse-
An open source equivalent of the Toshiba Port Replicator PA2703U. 

This is for Portege 610CT, T3400 and T3600 notebook/laptop computers. 

New versions (schematic, pcb files, test results etc) can be found here in the code repository https://github.com/dekkit/Mini-Port-Replicator-PA2703U-VGA-Keyboard-Mouse-
Versions: VA01 (initial prototype), VA02 (fixes, after initial tests),
VAxx (future versions will be in their own folders)

If you want to want to get a bunch of PCBs manufactured - simply use the latest GERBER.zip . Most manufacturers will provide an instant quote which is typically only a few dollars plus postage (postage is most expensive part). Or use the schematic to build your own breadboard version.

Please feel free to copy, adapt and use as appropriate . If you do improve on this design, please provide an acknowledgement, drop me a note / create an issue to let me know and share your results.

If you would like to develop your own version (customised for your specific video device, make a smaller SMD version), or simply to poke around to help further your own understanding (pick up on any errors too!) - I used the free app EasyEDA - I've opened up the project to make it easiser to clone and adapt - https://easyeda.com/dekkit/dek-s-port-replicator-pa2703u


Background

Given the great difficulty in sourcing the original port replicator for late 1990 era laptops, and the absence of having a vga out port on my laptop, this project aims to add a simple VGA out, keyboard, and mouse sockets via the propriatory socket found on the back of laptops from this era.

The original socket on my 610CT laptop used a propriatory socket and despite many hours spent searching for an equivalent,  I was unable to find anything suitable. 
As a result, I decided to recreate the socket using low cost pcb manufactoring, and particulary given the advancement in free online PCB design software (easyeda). This was based on the service manual and my own verification and testing.

The goal is to ensure this design is open, easily accessible, and able to be cheaply made. A secondary goal is to showcase how custom inexpensive PCBs can be easily made to support building an interface to a legacy / propriatory socket for other projects.

A notes about the Port Replicator PA2703U socket 
- The female socket has a total of 72pins, which is distributed across 4 rows.
- Width for each female slots is ~23mm (x 4)
- The female slots are grouped:  2x rows per group, with 36 pins (18 top, 18 bottom)
- There 18pins per female slot (x4)
- Pitch (gap between) each of the pins are 1.27mm
- 0.8mm to 1.0mm gap/space between upper and lower pins
- 2mm space needed between top group of pins and bottom group of pins

See the photos and schematic which will help make understanding this clearer.

Currently a PCB prototype has been produced and VGA is working! This project is still very much early stages.

Initial VA01 schematic (See VA01 folder for the first pcb - if you want to get one made)
https://github.com/dekkit/Mini-Port-Replicator-PA2703U-VGA-Keyboard-Mouse-/blob/main/Schematic_Dek's%20Mini%20Port%20Replicator%20PA2703U%20(VGA%20%2B%20Keyboard%20%2B%20Mouse)_2022-01-29.png

VA02 - currently WIP -see folder for interim versions

dek 31/01/2022
