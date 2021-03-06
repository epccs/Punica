# Description

This is a list of Test preformed on each Punica after assembly.

# Table of References


# Table Of Contents:

1. Basics
2. Assembly check
3. IC Solder Test
4. TBD

## Basics

These tests are for an assembled Punica board 17187^0 which may be referred to as a Unit Under Test (UUT). If the UUT fails and can be reworked then do so, otherwise it needs to be scraped. 

**Warning: never use a soldering iron to rework ceramic capacitors due to the thermal shock.**
    
Items used for test.

TBD


## Assembly check

After assembly check the circuit carefully to make sure all parts are soldered and correct, note that the device making is labeled on the schematic and assembly drawing.
    
NOTE: U1 is not yet on the board, so everything with +5V will not have power.


## IC Solder Test

U1 is not yet populated. Check that a diode drop to 0V is present from a circuit board pad that is connected to each of the pins of U2, U3, and U4 by measuring with a DMM's diode test set up for reversed polarity. Consult the schematic to determine which pins can be skipped (e.g. ground, power rail, ...).

This is the main test used for In-Circuit Testing (ICT). It becomes more valuable when the node voltage driven with the current source is recorded for each tested location and then used with statistics to determine test limits for that location. A relay matrix is needed to route the current source to the test points (e.g. probes, or pogo pins), but that will need some consideration.   
