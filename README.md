# Nextion-Barrett-950-interface

The Goal is to control the Barrett 950 transceiver with a Nextion Interface
You need:

  -Nextion device NXNX4832T035
  -DB35 male conenctor
  -A 4 cable wire (shielded is recomended)
  -RS232 to ttl converter
  
It is designed to be used with the 3.5" Device 
You only need 3 wires soldered in the Db25 connector
To power the unit from the radio you may use a downcoverter in order to get the 5V from the 13.8V from the radio (DB25 connector pin 23, ground pin 7)
To convert the signlas from the nextion to the radio you need a Max232 chip. Only the signal from TX from the NExtion is used, to the RX signal to the Radio side.

RADIO RX (DB25 pin 2) < -------RS232-------- <TX NEXTION







