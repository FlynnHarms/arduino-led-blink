# arduino-led-blink
My first arduino code ever written that blinks an led in series with a resistor.

#Components:
-Arduino Mega 2560 with USB Connector
-Red LED
-330 Ohm Resistor
-Wire Connectors

#Software
Arduino IDE

#Code
void setup() {
  // put your setup code here, to run once:
pinMode(13,OUTPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
digitalWrite(13,HIGH);
delay(1000);
digitalWrite(13,LOW);
delay(1000);
}

#HOW TO
-Wire pin 13 of Arduino to anode of LED(The long end).
-Place a resistor after in series with the cathode(short end).
-Connect the resistor to the GND pin of the Arduino.
-Write the Code above in the Arduino IDE. 
-Compile and run

#Summary
In this simple first adventure with the Arduino mega I wrote some simple code that blinks an LED on and off. I connected the Arduino Mega 2560 pin 13 to the anode end of the LED and placed a resistor in series after that is connected to arduino GND pin. Then sent the code to create the blinking effect. First setting the output pin and then run through a continuous loop of sneding high and low signals to the circuit to turn blink the LED on and OFF.

#SETUP

<img width="400" height="533" alt="ARDUINOLED" src="https://github.com/user-attachments/assets/862d2a6c-ab61-4835-a6f0-b482325ed776" />

Above is an image of the setup of the circuit.


