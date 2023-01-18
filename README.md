# Taito-PC030CM

This is a thru hole repro of the Taito PC030CM custom IC used on boards like Arkanoid, Bubble Bobble, Legend of Kage...
It handles coin input and counters and the boards won't boot without it
VIDEO ---> https://www.youtube.com/watch?v=ZvzLnMCHy0M

![download](https://user-images.githubusercontent.com/42693458/213310330-2928b3b7-9b83-49af-af75-7149b627adf6.png)

Parts needed:
 
 - R1, R7, R16, R19 = 470 ohm
 - R2, R8 = 4.7k
 - R4, R10 = 100 ohm
 - R5, R6, R17, R18 = 22K
 -  R9, R15, R20 = 1k
 - R11, R12, R13, R14 = 27 ohm ( 1 Watt )
 - ZD1, ZD2, ZD3, ZD4 = 1N4733 (zenner diode 5.1v)
 - D1,D2 = 1N4001 diode
 - IC A1 = MC14584 or 74ls14 - Shmidt trigger
 - IC A2 = ULN2003A - transistor array
 - IC B1 =  74ls07 / SN7417 - hex buffers 
 - IC B2 = 74LS08
 - C1,C2,C3,C4 = 1uf 50V Electrolytic capacitors
 - C6,C7,C8 = 103 (10nf) ceramic caps
