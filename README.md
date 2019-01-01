# nRF2401LCD

This sketch is used to test joystick and nRF24L01 radio module protoshields for the [carbot](https://github.com/WCRSyyc/carbot).  It reads inputs from the joystick, populates data packets, and sends them to the radio.  Another sketch and radio are needed to display the packet contents.

This code is based on the `GettingStarted` example from the RF24 library.  The functionality has been simplified, then extended to put the joystick readings in the message (packet) buffer.  Another radio module is needed to display the sent packet contents.