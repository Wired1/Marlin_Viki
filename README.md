Marlin_Viki
===========

Out of the the box working version of Marlin for AzteegX3 with the Viki panel.

Latest version set up to work straight out of the box with the Viki panel on an Azteeg X3. Uses the SD card on the Viki panel. Connect the two 6-pin to 6 loose pin plugs to the two headers on the back of the VIki panel. The loose end of the I2C header on the Viki connects to EXP3 on the Azteeg X3 as per the diagram http://files.panucatt.com/datasheets/x3v1_1_wiring_diagram.pdf. The loose end of the other header connects to three pins of the ICSP header on the X3 (refer to the above diagram again) as follows: Viki DI -> Azteeg MOSI, Viki DO -> Azteeg MISO & Viki CLK -> Azteeg SCK Viki CD -> Azteeg D49 & Viki CS -> Azteeg D53 (both below the ICSP header and next to the Azteeg SD card holder. The remaining lead from the SD header on the Viki BTN is connected to Azteeg D32 which is on EXP2.

In addition to this you need to remove the soldered link J12 on the reverse of the Azteeg X3 to disable the SD reader on the control board and enable the one on the Viki panel.

Happy printing, Simon (Wired1).
