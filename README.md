# Gate Sequencer

## Abstract
This is a 8-step gate sequencer for Eurorack.

Note that the current version needs a 16-pin power connector, as it directly 
draws from the 5V supply.

## Features
- The gate length of the incoming clock is preserved in the sequencer output
- Sequencer can be reset either via CV or pushbutton
- There is an inhibit switch which freezes the sequencer in its current step

## Technical Specifications
Module width: 6 HE

Input impedance (clock): 100k
Input impedance (reset): 10k

Output impedance: 1k

Power consumption:
-   5V: 4 mA
- +12V: 4 mA
- -12V: 0 mA
