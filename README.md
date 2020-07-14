# H-Bridge-using-MOSFET
a simple H-Bridge circuit using MOSFET
this H-bridge circuits is designed to rotate the motor in both directions
2 NMOSFETs and 2 PMOSFETs were used

the NMOSFETs used is : IRF540N ( it comes in a TO-220AB package) , it's date sheet : https://components101.com/sites/default/files/component_datasheet/IRF540N%20N-Channel%20Mosfet.pdf
the reasons for choosing it:
1- is has low threshold voltage (2.0) so it can be turened on by an arduino.
2- good performance with low voltage high current application ( Id = 33A @ 25c).
3- low package cost.

the PMOSFETs used is : IRF9540 (it comes in a TO-220AB package) , it's date sheet :
https://www.vishay.com/docs/91078/91078.pdf
the reasons for choosing it:
1- is has low threshold voltage (-2.0) so it can be turened on by an arduino.
2- good performance with low voltage high current application ( Id = -19A @ 25c).
3- low cost.
