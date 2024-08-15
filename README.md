NAME-NANDITHA.D
COMPANY NAME-CODTECH IT SOLUTIONS
ID-CT08DS5382
DOMAIN-EMBEDDED SYSTEM
DURATION-JULY 20 TO AUGUST 20th,2024

OVERVIEW OF PROJECT 
This project demonstrates how to control multiple LEDs using an Arduino, with additional functionality provided by a button to trigger different lighting sequences or patterns. It builds upon basic LED control by adding interactive elements like a button and more complex LED sequences.

Project Components:
1. Arduino Board (e.g., Arduino Uno)
2. 3 LEDs (connected to pins 7, 8, and 9)
3. 1 Push-button (connected to pin 4)
4. Resistors (for LEDs and pull-down resistor for the button)
5. Wires and Breadboard (for connections)
Functionality of the Project:
LED Control:

The project uses three LEDs connected to different pins of the Arduino.
The LEDs will turn on and off in predefined patterns, controlled by the Arduino.
Button Interaction:

A push-button is used to start or stop the LED sequences. When the button is pressed, the patterns begin to run; otherwise, all LEDs remain off.
LED Patterns:

Pattern 1 (Sequential Blinking): The LEDs blink one after the other in a sequence, giving a running effect.
Pattern 2 (All LEDs ON/OFF): All LEDs turn on together for 3 seconds and then turn off together for another 3 seconds.
Pattern 3 (Fast Blinking): All LEDs blink rapidly 5 times.
Project Logic:

The code continuously checks the button state. If the button is pressed, it triggers the patterns; if not, all LEDs are turned off.
The project repeats the patterns indefinitely as long as the button is held down or pressed.
How the Project Works:
Step 1: When the Arduino is powered on, it waits for the button to be pressed.
Step 2: When the button is pressed, the LED patterns start running in the sequence described:
Sequential blinking of LEDs.
All LEDs turn on and off together.
Fast blinking of LEDs.
Step 3: The patterns repeat until the button is released.
Step 4: When the button is not pressed, all LEDs remain off.
Applications and Learning Outcomes:
Basic Electronics: Learn how to connect LEDs and a push-button to an Arduino.
Microcontroller Programming: Understand how to write and structure code to interact with multiple outputs (LEDs) and inputs (button).
Pattern Control: Learn to create different LED blinking sequences.
User Interaction: Introduce user control via buttons to trigger specific actions.
 
