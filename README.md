# Modified SO-100 Robotic Arm with an Improved Gripper and ROS 2 Vision

<img width="3024" height="1614" alt="Robot_Pince_Horizontale_BLEU_2026-Oct-12_07-58-42AM-000_CustomizedView28347459514" src="https://github.com/user-attachments/assets/5a8f6200-943f-4c8e-9478-32a6bec51cec" />

This project aims to upgrade the SO-100 robotic arm with an improved gripper, a custom power distribution PCB, and a USB camera for AI-based vision.

I am developing a power distribution PCB designed to supply 12 V at 16 A, providing approximately 200 W to six Feetech STS3125 servomotors. Each servo has a maximum current draw of 2.7 A and a torque of 30 kg·cm. The servos communicate over a TTL bus, allowing them to be daisy-chained and controlled through a shared connection.

The robot will be controlled using ROS 2 running on a Raspberry Pi 4 Model B with 8 GB of RAM. As a bachelor's student in electronics and mathematics who wants to pursue robotics, I see this project as a practical way to learn ROS 2 and gain experience integrating hardware and software.

Foxglove will be used to monitor servo data and visualize the robot in 3D, making it easier to understand its behavior and troubleshoot issues.

To add computer vision capabilities, I have designed a camera mount for a USB webcam connected to the Raspberry Pi. I plan to use YOLO for object detection and train the model on images captured by the camera.

I also want to explore using OpenClaw to query an AI model through a command-line interface when detections are uncertain or confidence scores are low. This could help interpret ambiguous results and make interaction with the robot more intuitive.

##Planned system architecture
<img width="912" height="142" alt="Robot_SO100" src="https://github.com/user-attachments/assets/6b1df583-14e6-4e5b-a95f-22a369bb7d8c" />



##Power distribution PCB

<img width="855" height="585" alt="PCBPicture" src="https://github.com/user-attachments/assets/f6993297-2770-418b-849e-28a902309a6b" />

