switch_master.py is a program for configuring and controlling one or more switches via telnet session. Switches are usually either relays or solid state relays but can be anything that is abstractly considered a switch.

A json file controls the initial setup of all switches connected to the host. It is broken down by switch, each switch containing a number of pins. 
Each pin has a pin name for the Arduino board, has an active drive state, and additionally contains an alias for which it is known by the system of switches.

This software is licensed under the GPL v3.0 software license. The full license can be found in the same directory under gpl-3.0.txt 
