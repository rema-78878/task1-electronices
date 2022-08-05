# task1-electronices
to turn on the servo motor you will use:
Arduino 
servo motor 
the code:
#include <Servo.h>

Servo myservo;  // create servo object to control a servo
// twelve servo objects can be created on most boards

int pos = 0;    // variable to store the servo position

void setup() {
  myservo.attach(9);  // attaches the servo on pin 9 to the servo object

   myservo.write(90);
}

void loop() {}

and this code will make the servo rotate at an angle of 90 degrees.

