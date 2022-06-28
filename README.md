# Brushless_DC_motor

To control the Brushless DC motor (BLDC), several components are needed:

1- Arduino 
2- ESC 30A motor control 
3- battery
4- wires
5- BLDC motor

as the uploaded picture shows,
the ESC 30A is connected to BLDC motor, the ESC 30A is powered by external battery and controled by the Arduino.

the ESC 30A accepts PWM signal to generate AC signal at the motor terminals.
The PWM signal determines the speed of the motor.

Since the servo library generates PWM signal similars to the one that is accepted by the ESC 30A, the ESC 30A is controled by a servo object.

the code runs the motor and changes its speed perodically from low to high speed and visa versa


