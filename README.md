# Sid's Hackboard
My hackboard is pretty closely based on my current keyboard (Steelseries Apex 3 TKL) because it fits very well for what I need it to do. Probably could have optimized it more but ran out of time.                         
I'll probably make some keys macros especially the cluster around Delete.                   
It also includes a volume knob + a switch for play/pause, skip, and rewind.                         
This was actually way easier than hackpad because I now use KiCad and Fusion a lot more (even for other projects), but figuring out how to do the integrated plate was a bit annoying, and drafting the edges also took some figuring out.                      
Anyway I made a (hopefully) functional keyboard.                    

## Key Features:
* Standard TKL layout
* Plate with integrated case
* Magnetic lift bar - totally not copied from s76
* Volume knob
* Probably way too tall but I didn't bother to measure properly

## CAD/case:
M3 (M5? idek) bolts and heatset inserts are used to hold the 2 pieces together, and an integrated plate is used to hold the pcb.

## PCB:
A matrix is wired to prevent ghosting - the wiring took way too long. There are 84 total keys and one rotary encoder + switch, organized in 17 columns and 6 rows.

## Firmware:
KMK was used for the firmware, I still need to figure out how to implement the volume controls though.

## BOM:
|ITEM|QTY|PRICE|
|----|---|-----|
|Orpheus Pico|1|price|
|mx switches|qty|price|
|stabs|qty|price|
|encoder|qty|price|
|3x10x60mm Magnets|1 pack of 4|5.99|
|1N4148 diodes|qty|price|
|keycaps|qty|price|
|bolts|qty|price|
|heatset inserts|qty|price|

## Images:
Fully assembled:          
<img src="images/full.png" width="350">               
Schematic:          
<img src="images/schematic.png" width="350">                           
PCB:            
<img src="images/pcb.png" width="350"><img src="images/pcb3d.png" width="350">                                                   
Case:                                                     
<img src="images/case.png" width="350">          