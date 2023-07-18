This file contains three subfiles. 

First subfile contains the Abstract and Design for the project. 


Second subfile contains the logisim circuit files of the project which again contains 2 parts. The first circuit is a detector which gives an output of 1,
if there is an empty parking slot and 0 otherwise. If parking spot is found, the time for which the car is parked is taken as input . The ticket price is then calculated based on
a pre-set metirc with price p (fixed price for the first hour) and q (price for the subsequent minute). After this, final price is printed. 

All logisim files need a logisim simulator downloaded on the system to run them. The files are in *.circ extension.

Third subfile contains all the verilog code in .v format for the components used in the project.

It can be opened and viewed with Icarus iverilog installed on the system. 

commands to run the verilog code - 

//open the location where the verilog file is saved.

On the terminal give these commands - 

iverilog ticketcalculator.v ticketcalculator_tb.v
iverilog detector.v detector_tb.v

//This will give the output for the verilog code.