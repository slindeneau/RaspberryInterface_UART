# RaspberryInterface_UART
Code library for reading and writing from a generic UART interface.


How to build

g++ -c Interface_UART.cpp


ar -cq libInterface_UART.a Interface_UART.o

How to link to & use

Include the extra library folder containing the Interface_UART library using -L

Then build using the -lInterface_UART
