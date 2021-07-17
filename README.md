# Nrf-Multiwii-Airplane
This is Multiwii 2.4 code modified to work with Nrf24l01 for Airplanes.

This is modified to work with Nrf CE,CSN on pins(10,7) and ***Airplane Motor on pin 9,
rudder on pin (3), both Wings use same pin (5) and Aileron on pin(6)*** of Atmega 328.

The code is compatible to work with nrf on following devices:
Arduino Uno ,Nano ,Promini .etc using Atmega328.

This code eliminates the use of an external Receiver and performs recieving and flight controlling on 
a single board / single atmega328.

After uploadng and connecting to multiwii gui, if no imu values are being received,
then there's an issue with the nrf module or it's wiring.
If you are receiving values and Aux4 is high ,then nrf is connected to transmitter 
else if Aux4 is low then no signal is being recieved from transmitter.
