
###  DATE: 

###  NAME: VISHNU VARDHAN S
###  ROLL NO : 212221220059
###  DEPARTMENT: INFORMATION TECHNOLOGY
# Experiment-no-6-DC-Motor-Speed-Control-Using-Arduino
### AIM : To control the speed and the direction of a DC motor using L293D driver ic( H- bridge)

### Components Required:
•	Arduino UNO board
•	L293D driver
•	12V DC motor
•	10K ohm potentiometer
•	Pushbutton
•	12V source
•	Breadboard
•	Jumper wires
### THEORY 
The L293D quadruple half-H drivers chip allows us to drive 2 motors in both directions, with two PWM outputs from the Arduino we can easily control the speed as well as the direction of rotation of one DC motor. (PWM: Pulse Width Modulation).
Arduino DC motor control circuit:
Project circuit schematic diagram is the one below.

![image![WhatsApp Image 2024-03-21 at 11 38 29 AM](https://github.com/AllenSteve18/Experiment-no-7-DC-Motor-Speed-Control-Using-Arduino/assets/131678601/af23ce48-6420-4d79-b141-00560627284c)

FIGURE-01 H BRIDGE CIRUCIT INTERFACE 
 
The speed of the DC motor (both directions) is controlled with the 10k potentiometer which is connected to analog channel 0 (A0) and the direction of rotation is controlled with the push button which is connected to pin 8 of the Arduino UNO board. If the button is pressed the motor will change its direction directly.
The L293D driver has 2 VCCs: VCC1 is +5V and VCC2 is +12V (same as motor nominal voltage). Pins IN1 and IN2 are the control pins where:
![image![WhatsApp Image 2024-03-21 at 11 38 31 AM](https://github.com/AllenSteve18/Experiment-no-7-DC-Motor-Speed-Control-Using-Arduino/assets/131678601/baddac58-8123-40a4-bd4b-f30b07228eff)

TABLE-01 EXITATION TABLE FOR H BRIDGE 

As shown in the circuit diagram we need only 3 Arduino terminal pins, pin 8 is for the push button which toggles the motor direction of rotation. Pins 9 and 10 are PWM signal outputs, at any time there is only 1 active PWM, this allows us to control the direction as well as the speed by varying the duty cycle of the PWM signal. The active PWM pin decides the motor direction of rotation (one at a time, the other output is logic 0).

### PROGRAM 

### OUTPUT

### GRAPH AND TABULATION 


![image![WhatsApp Image 2024-03-21 at 11 38 30 AM](https://github.com/AllenSteve18/Experiment-no-7-DC-Motor-Speed-Control-Using-Arduino/assets/131678601/6d51bb0e-a98e-4895-a266-43ae2eb861ac)

![image]

![WhatsApp Image 2024-03-21 at 11 38 30 AM (1)](https://github.com/AllenSteve18/Experiment-no-7-DC-Motor-Speed-Control-Using-Arduino/assets/131678601/f54bbf4d-23ab-42a5-b489-e190d19f3fce)

### RESULTS AND DISCUSSION 

