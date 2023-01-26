# Line Follower 

### This was the last project of Introduction to Robotics course: Line Follower.

## Description 
 - A line follower project is a robot that is designed to follow a line on the floor (or maybe on walls, if it's very fancy). The robot uses sensors to detect the location of the line and then adjusts its movement in order to remain in the middle. 
 - We used a PID controller  - a control loop feedback mechanism that keeps the robot on the line. 
 
 ## Components 
 - Arduino Uno
 - 2 DC motors
 - 2 wheels
 - LiPo Battery
 - QTR-8A reflectance sensor (8 IR array)
 - L293D motor driver
 - wires, breadboard, chassis

 ## Features & Parameters 
 - We made an automatic calibration for a few seconds by powering the right motor until the sensor is out of the line and after we power the left motor and so on.
 - Then we move the car left or right until the sensor is centered on the line.
 - We map the error from sensors to [-75, 75] interval and apply PID with kp = 20, ki = 0, kd = 5. 
 - For a better approach in tight turns, we spin one motor forward and the other backwards.

<br>

## Some pictures of the line follower:
![325478971_918743152631359_8031467375237460162_n](https://user-images.githubusercontent.com/99658689/213774646-882afc95-d5bb-4228-b793-d206cf2be099.jpg)
![325555571_1877325329274192_2172384486957569340_n](https://user-images.githubusercontent.com/99658689/213774650-b90faca9-74c0-4abb-bc9d-f275100150a5.jpg)
![325475183_514660490809337_4532274917769929807_n](https://user-images.githubusercontent.com/99658689/213774652-0b43f558-b242-4fca-9955-a2315c473824.jpg)


 <div align="center">
  <h3>
    <a href="https://youtube.com/shorts/LLG73cJCmWs">
      Here's a video of the line follower doing its best!
    </a>
  </h3>
</div>

## Team name: Andre
## Colleague GitHub: https://github.com/andreiroman103/LineFollower-Robotics

