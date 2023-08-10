# fp_util
Yet another Arduino control utility for the Eltek Flatpack2 power supply.

Manage an Eltek Flatpack 2 power supply via an MCP2515 CAN controller chip.

This should work with all Arduino-type shields, as long as the CS & INT pins are correct.

You'll need to install the mcp_can and LibPrintf libraries (simplest method is 
via the Arduino IDE).

Derived from https://github.com/the6p4c/Flatpack2/blob/master/Arduino/fp2_control/

Information sources:
* https://github.com/neggles/flatpack2s2/blob/main/docs/Protocol.md
* https://github.com/the6p4c/Flatpack2/blob/master/Protocol.md
* https://openinverter.org/forum/viewtopic.php?t=1351
* https://github.com/neggles/flatpack2s2
* https://github.com/tomvanklinken/Flatpack2

