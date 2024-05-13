# DEC-Rainbow-HDD-Cable-Adapter
This PCB can be used to connect an MFM hard drive (or emulator) to a Dec rainbow 100 using standard ribbon cables.

I followed the cable building guide found here: https://oldcomputers-ddns.org/public/pub/mirror/os2site/sw/dec/rainbow/rainbow.faq

![rbmfm](https://github.com/alitel/DEC-Rainbow-HDD-Cable-Adapter/assets/161774022/38348a40-1006-42df-8cf5-12b75a35fb82)


From the guide linked above:

        Here's the schematics:

        r = Red mark on flat ribbon cable.
        M = Mark on the connectors (for pin nr 1).
        o = PIN which is used.
        / = PIN not used, do NOT cut the cable line, it's the pin on the
                  connector which is not used...

 Cut between as shown________________________________________
                            |   |                   |       |
                            V   V                   V       V
                   1 1 1 1 1 1 1 1 1 1 2 2 2 2 2 2 2 2 2 2 3 3 3 3 3  FLAT
 1 2 3 4 5 6 7 8 9 0 1 2 3 4 5 6 7 8 9 0 1 2 3 4 5 6 7 8 9 0 1 2 3 4  RIBBON
 | | | | | | | | | | | | | | | | | | | | | | | | | | | | | |_______
 o o o o o o o o o o o o o o | | o o o o o o o o o o | | |________ \ 
 | | | | | | | | | | | | | | | | | | | | | | | | | | | |_________ \ \
 r | | | | | | | | | | | | | | | | | | | | | | | | | |__________ \ \  to 20
 | | | | | | | | | | | | | | | | | | | | | | | | | |            \ \  pin card
 r | | | | | | | | | | | | | | | | | | | | | | | | |             \  edge
 | | | | | | | | | | | | | | | | | | | | | | | | | |               connector
 r | | | | | | | | | | | | | | |_|_|_|_|_|_|_|_|_|_|________________
 | | | | | | | | | | | | | | |___|_|_|_|_|_|_|_|_|_|______________ |
 r | | | | | | | | | | | | |     | | | | | | | | | |             | |
 | | | | | | | | | | 1 | 1 |     1 | 1 | 2 | 2 | 2 |             3 4
_1_|_3_|_5_|_7_|_9_|_1_|_3_|_____7_|_9_|_1_|_3_|_5_|_____________3_4_
|M                                                                  |
|               34 PIN CARD EDGE CONNECTOR                          |
---------------------------------------------------------------------



        The 20 pin card edge connector:
                                             2 2     2 3  Cable line
                                             7 8     9 0  numbers
                                             | |     | |
                                             | |     | |
                                       1   1 | 1   1 | 1   2
                    ___2___4___6___8___0___2_|_4___6_|_8___0_
                    |M                       | o     | o    |
                    |                        o       o      |
                    -----------------------------------------
                                         1   1   1   1   1
                     1   3   5   7   9   1   3   5   7   9

        Finally the 34 pin connector for the controller card, just
        make sure the mark on the cable is lined up with the nr 1
        pin on the connector.

        
