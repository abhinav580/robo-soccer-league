# robo-soccer-league
Welcome to the Robo Soccer League 2019. In this Documentation you will get every information about this Event and How to make the Bot for the event.

# Requirements
1. [Arduino UNO](https://www.amazon.in/Uno-ATmega328P-Compatible-ATMEGA16U2-Arduino/dp/B015C7SC5U/ref=sr_1_3?keywords=arduino+uno&qid=1566483575&s=gateway&sr=8-3)
2. [Chasis for Bot](https://www.amazon.in/gp/product/B01MT9Z9QB/ref=ox_sc_act_title_3?smid=A334DB6ZJ8V2ML&psc=1)
3. [Motor Driver](https://www.amazon.in/gp/product/B00N4KWYDE/ref=ox_sc_act_title_1?smid=A3II2Q67VJD3XT&psc=1)
4. [Bluetooth Module](https://www.amazon.in/dp/B019OR9YVU)
5. Jumper Cables

# Bot Setup
Circuit Diagram:
![alt text](https://www.electronicshub.org/wp-content/uploads/2018/08/Bluetooth-Controlled-Robot-using-Arduino-Circuit-Diagram.jpg)
First is the HC-05 Bluetooth Module. The +5V and GND pins of the Bluetooth Module are connected to +5V and GND of Arduino.
Now, the L298N Motor Driver Module. Digital I/O Pins 9 through 12 of Arduino are configured as Input pins of the Motor Driver and are connected to IN1 through IN4 of the L298N Motor Driver Module. Both the Enable Pins are connected to 5V through provided jumper.

The robot chassis which I am using in this Bluetooth Controlled Robot Car project is supplied with 4 geared motors. Since L298N has slots for only two motors, I have joined the left side motors as one set and the right side motors as other set and connected both these sets to the output of L298N Module.


NOTE: I have used L298N Motor Driver Module to drive the motors of the robot. You can use either this one or L293D Motor Driver Module. If you are using L293D, then check out for the connections.

# Installation
Download the [Arduino IDE](https://www.arduino.cc/en/Main/Software) by visiting the Link and install it in your System
Download the [Android App](https://www.youtube.com/redirect?event=video_description&redir_token=Wt1QDh4OWZsq5_V69gf6GA1q1Kd8MTU2NjU3MzUxOUAxNTY2NDg3MTE5&q=https%3A%2F%2Fplay.google.com%2Fstore%2Fapps%2Fdetails%3Fid%3Dappinventor.ai_el_profe_garcia.Arduino_Control_Car%26hl%3Den&v=kewza7RyKMQ)
Connect with the Bluetooth and Control Your Bot!
