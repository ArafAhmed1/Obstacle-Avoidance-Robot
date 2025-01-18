# Obstacle-Avoidance-Robot
Using Arduino, Ultrasonic sound sensor, Servo Motor and a Bluetooth Module I built this Obstacle Avoiding Robot that can also be controlled manually by using a Remote Controller and Voice control via bluetooth

This project uses Obstacle(), Bluetoothcontrol() and Voicecontrol() functions to make the robot Avoide obstacles, let a remote controller control it and a voice command control it via bluetooth. 
You can use one of this functions at a time. 
In the loop function at line 43 just let the function be there which one you want to use and comment out the other two.

for example:
void loop() {
  Obstacle();
  // Bluetoothcontrol();
  // voicecontrol();
}

It will run the function that is in the function not commented out.

Here is a video link of the robot avoiding obstacles: https://youtube.com/shorts/qDH5Dgyotp0?feature=share
Video of the robot being controlled via android remote control app via bluetooth: https://youtube.com/shorts/U4Fgk2mbna8?feature=share
Video of the robot being controlled via voice command via bluetooth: https://youtube.com/shorts/2jyEfM5uwz4?feature=share
