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

Releases
- VA01 Schematic + PCB - initial working  version (See VA01 folder for the first prototype pcb)
- VA02 Schematic + PCB - most recent WIP version (See VA02 folder for the latest prototype pcb) -  currently being tested! 



Build Instructions (WIP)

The PCB has been designed to be snapped apart into sections (much like a car model building kit).
In addition to the BOM you will need nylon/plastic stand off/screw kit or something you can wedge in between the pcb layers. 

1. Gently bend the 'TOP' section of the PCB until it snaps off.
2. Gently bend the 'BOTTOM' section of the PCB until it snaps off.

... you should now have 3 x PCB parts! 

3. Insert 2 x nylon screws through each of screw holes of the 'TOP' PCB.
4. Insert a nylon nut of 2mm thickness to hold the screw against the 'TOP' PCB (this is used to create a 2mm gap between the 'TOP' PCB and 'BOTTOM' PCB...alternatively can use spare plastic card or something else to create a gap between the 2 x pcb)
5. insert a 6 pin IDC header on the 'BOTTOM' pcb (alternatively you can skip this step and later use bridging wire or spare capacitor / resistor legs to electrically join the top/bottom layers).
6. Place 'TOP' PCB over the 'BOTTOM' PCB.
7. Insert an additional 2 x nylon nuts or PCB stand offs to screw the 2 x PCB parts together.

..test / check  to make sure both pcbs line up and fit within with the laptop socket.  DO NOT PROCEED to solder until you are comfortable with the fit.

8. Solder the 6pins (CN1 and CN2) to connect the 'TOP' pcb to the 'BOTTOM' PCB.
9. Solder the remaining  sockets and parts.

See 'Build Photos' folder (for examples of build)

dek 13/02/2022
