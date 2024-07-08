# Electronics-track
#### Task 1 in the electronics track \
##### Write an algorithm for operating servo motors to drive the robot
###### 1. Identifying the number and locations of servo motors:
###### - Robots typically require servo motors at key joints
###### - The number and locations of the motors must be accurately determined to ensure the desired movement

###### 2. Connecting the servo motors to the central control unit

###### 3. Programming the walking motion control algorithm:
###### - Defining the required walking stages (such as lifting the leg, shifting weight, stabilizing the leg) and repetitions and angles

###### 4. Implementing the balance control algorithm
###### - Using motion and balance sensors

###### 5. Coordinating joint movements

###### 6. Learning and adaptation

###### 7. Execution and testing
###### - Testing the walking and balance motion and making necessary adjustments.

###### // Algorithm for servo motor
###### // Importing the servo motor control library
###### // Defining variables for servo motors
###### // Creating an object for control
###### // Configuring the servo motor control interfaces
###### // Running the algorithm for walking motion
###### // Servo motor control function

###### // Walking motion algorithm
###### // Step 2: Advancing the right leg
###### // Step 3: Lifting the left leg
###### // Step 4: Advancing the left leg

#### Task 2 in the electronics track \
##### Connect and program an electronic circuit containing 6 servo motors on the simulation program

#### Circuit programming code:
```
#include <Servo.h>

Servo myServo1, myServo2, myServo3, myServo4, myServo5, myServo6;

void setup() {
  myServo1.attach(12);
  myServo2.attach(11);
  myServo3.attach(10);
  myServo4.attach(9);
  myServo5.attach(8);
  myServo6.attach(7);
}

void loop() {
  for (int pos = 0; pos <= 90; pos += 1) {
    myServo1.write(pos);
    delay(15);
  }
  for (int pos = 90; pos >= 0; pos -= 1) {
    myServo1.write(pos);
    delay(15);
  }

  for (int pos = 0; pos <= 90; pos += 1) {
    myServo2.write(pos);
    delay(15);
  }
  for (int pos = 90; pos >= 0; pos -= 1) {
    myServo2.write(pos);
    delay(15);
  }

  for (int pos = 0; pos <= 90; pos += 1) {
    myServo3.write(pos);
    delay(15);
  }
  for (int pos = 90; pos >= 0; pos -= 1) {
    myServo3.write(pos);
    delay(15);
  }

  for (int pos = 0; pos <= 90; pos += 1) {
    myServo4.write(pos);
    delay(15);
  }
  for (int pos = 90; pos >= 0; pos -= 1) {
    myServo4.write(pos);
    delay(15);
  }

  for (int pos = 0; pos <= 90; pos += 1) {
    myServo5.write(pos);
    delay(15);
  }
  for (int pos = 90; pos >= 0; pos -= 1) {
    myServo5.write(pos);
    delay(15);
  }

  for (int pos = 0; pos <= 90; pos += 1) {
    myServo6.write(pos);
    delay(15);
  }
  for (int pos = 90; pos >= 0; pos -= 1) {
    myServo6.write(pos);
    delay(15);
  }

  delay(2000); 
}
```
<img src="https://github.com/Samar-Hamed2003/Electronics-track/assets/173670288/a27caa8c-ee31-49d7-9e2e-2bfaa437c0aa.jpg" width="25%" height="25%">

#### Using the TinkerCAD program, we designed the following electrical circuits:
<img src="https://github.com/Samar-Hamed2003/Electronics-track/assets/173670288/69f600ae-00e8-41b3-b341-5cf8c8c746c2.jpg" width="50%" height="50%">

#### Click to enter the tinkercar website
https://www.tinkercad.com/things/h9skiVjUw3N-neat-gaaris-turing/editel

