Main developer: Napoleón Ramírez
Other developers: Federico Mingramm, Andrés Cárdenas

mS-Reacher is an open source Cylindrical robot.



Open "General Robot v1.vio" with vBuilder software (https://velocio.net/vbuilder/).

Look for subDemo subroutine for an example on how to implement your own sobroutines.



The brain of the robot is the ACE 22 Velocio PLC.



___Wiring:

inputs:
B1 - endswitch Radius
B2 - endsiwtch Theta
B3 - endswitch Zeta

outputs:
D1 - Step for Radius motor
D2 - Direction for Radius motor
D3 - Step for Theta motor
D4 - Direction for Theta motor
D5 - Step for Zeta motor
D6 - Direction for Zeta motor