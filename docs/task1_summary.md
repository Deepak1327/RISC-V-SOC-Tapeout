# Task-1: GitHub Repo Setup & Video Summary

Created the GitHUb repository with the help of chatGPT.
followed the instructions and command such as:-
clone
add
commit
push 
# Video Summary:-
Discussed abot GCC:- GNU Compiler COllection
Understand the term "Silicon Proven" and it's importance.
O0-We will first model the specification in C kind of format, not in verilog.
O1:-Testbench we will write in C language, and it can be of ARM GCC, X86 gcc any processor architecture.
so output at stage O0 == O1 this is the main task of step 1 and step 2.
O2:- Soft copy of RTL after understanding the hardware, Verilog or other industry level HDL.
Hardware:- Gates and all
Software:- Representation of the specification in any HDL language.
Run the application on hardware which we designed through specs and hdl code.
and result should be O2 == O1.
O3:- SoC design Flow:- separate out Processor and preipherals/IP.
Processor:- Verilog code should be "Synthesisable":- Can be converted to gate levels.
Peripherals:- Macros:- Synthesisable RTL(MUX, FF etc.) and IPs:- Functional RTL(like ADCs,PLL etc)
Now integration of all the above blocks according to their location and we will get SoC.
Purpose O3 == O2 == O1

Difference between processor and controller.
micro-processor:- 8085/8086(Only CPU)
micro-controller:- 8051(CPU with Peripherals)
 
Now RTL To GDS
Floorplanning, Placement, CTS,STA, Routing.
only Transistors, metal layers, poly layer etc.
Output file is Graphical Datastream Informaiton Interchange.
This file has information for Foundry to make the Final IC. This GDSII will go through DRC/LVS checks.
After checking Design will go for Tapeout, then Tapein Then testing with the help of test board.
Then in testing step our output will be O4 and O4 == O3 == O2 == O1.
Market:-
Iwatch, Home Appliances(AC,TV,etc).
Use of the IC will be at low frequency application ranging from 100-130 MHz.