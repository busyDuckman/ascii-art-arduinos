# Master files for 'ASCII art Arduinos'.  
##Notes:  
**Project home:** [http://busyducks.com/ascii-art-arduinos](http://busyducks.com/ascii-art-arduinos)  
**Author:** Dr Warren Creemrs (duckman)  
**Licence:** CC-BY cite: http://busyducks.com/ascii-art-arduinos  
**NB:** Just put http://busyducks.com/ascii-art-arduinos in a readme or something, it does not need to hang around next to the image.  
  
**Ver:** 1.2  
**Github:** https://github.com/busyDuckman/ascii-art-arduinos  
**Facebook:** https://www.facebook.com/BusyDucks/  
**See also this write up on the Arduino Blog:** https://blog.arduino.cc/2015/11/20/arduino-pinout-ascii-art-ready-to-go/  
  
##Example:                         

                                      +-----+
         +----[PWR]-------------------| USB |--+
         |                            +-----+  |
         |         GND/RST2  [ ][ ]            |
         |       MOSI2/SCK2  [ ][ ]  A5/SCL[ ] |   C5 
         |          5V/MISO2 [ ][ ]  A4/SDA[ ] |   C4 
         |                             AREF[ ] |
         |                              GND[ ] |
         | [ ]N/C                    SCK/13[ ] |   B5
         | [ ]IOREF                 MISO/12[ ] |   .
         | [ ]RST                   MOSI/11[ ]~|   .
         | [ ]3V3    +---+               10[ ]~|   .
         | [ ]5v     | A |                9[ ]~|   .
         | [ ]GND   -| R |-               8[ ] |   B0
         | [ ]GND   -| D |-                    |
         | [ ]Vin   -| U |-               7[ ] |   D7
         |          -| I |-               6[ ]~|   .
         | [ ]A0    -| N |-               5[ ]~|   .
         | [ ]A1    -| O |-               4[ ] |   .
         | [ ]A2     +---+           INT1/3[ ]~|   .
         | [ ]A3                     INT0/2[ ] |   .
         | [ ]A4/SDA  RST SCK MISO     TX>1[ ] |   .
         | [ ]A5/SCL  [ ] [ ] [ ]      RX<0[ ] |   D0
         |            [ ] [ ] [ ]              |
         |  UNO_R3    GND MOSI 5V  ____________/
          \_______________________/          
                                                                        
                                                                        
          HTTP://BUSYDUCKS.COM/ASCII-ART-ARDUINOS                  
                                                                        
