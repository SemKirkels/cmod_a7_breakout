# cmod_a7_breakout
The breakout board is designed for the Digilent CMOD A7. The DIP 48 headers will be brought to various components such as:  A seven-segment display, additional LEDs (8 yellow and 2 RGB), Additional push buttons and switches and a PMOD header.  

In this repo, you will find the gerber files, bill of materials, a KiCad project and a custom XDC file for the breakout board.  
At a later stage, AXI4-Lite blocks will be provided to interact with the various components on the board.

Check the list below to see what has been provided so far.
    
-[] Schematics & PCB-Design
-[] Gerber files
-[] Custom XDC
-[] AXI4-Lite blocks

The table below shows the different connections of the board.

| Component             | DIP Pin |     | DIP Pin | FPGA Pin          |
|-----------------------|---------|-----|---------|-------------------|
| LED [3]               | 1       |     | 48      | Seven segment [G] |
| LED [4]               | 2       |     | 47      | Seven segment [F] |
| LED [5]               | 3       |     | 46      | Seven segment [E] |
| LED [6]               | 4       |     | 45      | Seven segment [D] |
| LED [7]               | 5       |     | 44      | Seven segment [C] |
| LED [8]               | 6       |     | 43      | Seven segment [B] |
| LED [9]               | 7       |     | 42      | Seven segment [A] |
| LED [10]              | 8       |     | 41      | PMOD B [10]       |
| BTN [3]               | 9       |     | 40      | PMOD B [9]        |
| BTN [4]               | 10      |     | 39      | PMOD B [8]        |
| BTN [5]               | 11      |     | 38      | PMOD B [7]        |
| BTN [6]               | 12      |     | 37      | PMOD B [4]        |
| BTN [7]               | 13      |     | 36      | PMOD B [3]        |
| BTN [8]               | 14      |     | 35      | PMOD B [2]        |
| ADC                   | 15      |     | 34      | PMOD B [1]        |
| ADC                   | 16      |     | 33      | DIP [8]           |
| RGB B [R]             | 17      |     | 32      | DIP [7]           |
| RGB B [G]             | 18      |     | 31      | DIP [6]           |
| RGB B [B]             | 19      |     | 30      | DIP [5]           |
| RGB C [R]             | 20      |     | 29      | DIP [4]           |
| RGB C [G]             | 21      |     | 28      | DIP [3]           |
| RGB C [B]             | 22      |     | 27      | DIP [2]           |
| Seven segment [DP]    | 23      |     | 26      | DIP [1]           |
| VU                    | 24      |     | 25      | GND               |

*The numbering includes the onboard LEDs and Buttons.
