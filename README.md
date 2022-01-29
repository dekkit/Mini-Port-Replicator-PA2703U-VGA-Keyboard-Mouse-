# Mini-Port-Replicator-PA2703U-VGA-Keyboard-Mouse-
An open source equivalent of the Toshiba Port Replicator PA2703U. 

This is for Portege 610CT, T3400 and T3600 notebook/laptop computers. 

Given the great difficulty in sourcing the original port replicator for late 1990 era laptops, and the absence of having a vga out port on my laptop, this project aims to add a simple VGA out, keyboard, and mouse sockets via the propriatory socket found on the back of laptops from this era.

The original socket on my 610CT laptop used a propriatory socket and despite many hours spent searching for an equivalent,  I was unable to find anything suitable. 
As a result, I decided to recreate the socket using low cost pcb manufactoring, and particulary given the advancement in free online PCB design software (easyeda). This was based on the service manual and my own verification and testing.

The goal is to ensure this design is open, easily accessible, and able to be cheaply made. A secondary goal is to showcase how custom inexpensive PCBs can be easily made to support building an interface to a legacy / propriatory socket for other projects.

Note while source files will be provided here, I'll include link to the easyeda repository will also be made available to support cloning/modification etc.


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

dek 29/01/2022
