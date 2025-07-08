# Line Follower Robot

A mini-robot inspired by WALL-E built to follow a designated path using IR sensors and gesture control. This project was developed as part of the IC152 Makerspace course by B3 Group I.

## Group Members

- Varad Pendse (230003084)  
- Varikuti Reethika Prasanna (230003085)  
- Vedansh Shrivastava (230003086)  
- Vangalapudi Abhitha (230003081)  
- Vanka Abhinaya Sri (230003082)  
- Vanshika Agrawal (230003083)

## Project Introduction

A Line Follower Robot is a mobile robot designed to detect and follow a path marked on the floor. This model mimics the behavior of WALL-E, integrating gesture-controlled movements through IR sensors placed in the "eyes" of the robot. Additionally, the Blynk App is used to wirelessly control the robot using a smartphone.

## Equipment Used

- IR Sensors  
- Arduino UNO  
- Motor Driver (L298N)  
- Gear Motors  
- Jumper Wires  
- Battery Holder  
- Wheels  
- Lithium Batteries  
- Wi-Fi Module  
- Ultrasonic Sensors  

## Procedure

1. Designing chassis, eyes, neck, and wheels using Fusion 360.
2. Chassis was laser-cut and parts were 3D printed.
3. Attach motors and wheels to the chassis.
4. Mount the IR sensors on the front of the robot, facing downward.
5. Connect the IR sensors to Arduino input pins.
6. Connect the motor driver to Arduino and motors.
7. Write code to control motor movement based on sensor input:
   - If both sensors are on or off the line, move forward.
   - If the left sensor is off the line, turn right.
   - If the right sensor is off the line, turn left.
8. Control the robot using gesture sensing and the Blynk app.

## Component Drawings

CAD models and technical drawings of the robot body and parts were created using Fusion 360.

(You can attach or link component drawing images here if available.)

## Demo Video

(Upload the video or provide a YouTube or Google Drive link here.)

## Key Learnings

- Hands-on experience in 3D printing, laser cutting, and CAD modeling.
- Learned how to integrate electronic components like Arduino, motor drivers, and sensors.
- Understood the impact of design on robot movement and effectiveness.
- Improved collaboration and teamwork skills.

## Acknowledgements

Thanks to our instructors and mentors at IC152 Makerspace for their support throughout the project.

## License

This project is for educational purposes. Contact group members for reuse or collaboration.
