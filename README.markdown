Java2Arduino
------------

java2arduino is a communication application programming interface (API)
that allows you to execute code on a microcontroller and also exchange arbitrary data with it
via different means of communications (currently supported are serial links over Bluetooth (BT) and USB).

It can be divided into two major parts: The client side can use the API to execute
functions on the server side and to send and receive data from it. The server side implements the API
on the microcontroller and allows to easily add user generated functions that can then be called by the client.

The server part is written in C and is designed to be run on Atmel AVR microcontrollers,
which are used among others by the <a href="http://www.arduino.cc">Arduino project</a>.
This is also the origin of the namem but java2arduino is in no way limited to Arudino platforms.
The client part is written in Java standard edition (earlier versions also supported Java mobile edition).

For more information please run `make` in the `doc` folder to generate the full documentation with Doxygen.