# keyboard_midi001
sketch to test basic keyboard matrix using teensy and output midi across usb

You can configure the row and column pins for the switch matrix implementation to however your key board is setup: see lines 31, 32: my keyboard has 49 keys, in rows of 6, except for the last key which is on it's own.

Be wary of how the rows/columns are setup: test all diode orientations etc. before running, otherwise risk shorting the Teensy.
