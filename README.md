# OPC_Client
This software gives an ability to connect to UVP280-device through EKON134 and download a report from it. 
UVP280 and EKON134 communicate via serial port. UVP280 and OPC_Client communicate via ethernet. 
Software send a request to specific Modbus registers on UVP280 and recieve a report as an answer. Results of a request stores in a SQLite database.
Software communicate with 5 separate devices. 
In options user can specify serial ports, time of request, delay time and devices which will be interrogated.
