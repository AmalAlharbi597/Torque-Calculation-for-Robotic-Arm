# Torque-Calculation-for-Robotic-Arm

Given Data:

Arm Lengths:

First arm: ( 15 cm ) (( 0.15 m )).
Second arm: ( 10 cm) (( 0.10 m)).
Third arm: ( 4 cm ) (( 0.04 m )).
Hanging Weight: ( 1 kg).

Gravitational Acceleration: ( g = 9.81 m/s^2 ).

Step 1: Calculate the Force ( F )

The force acting due to the hanging weight is calculated as:

![image](https://github.com/user-attachments/assets/a9882db9-12bc-46ce-a785-4137d2a971aa)



Step 2: Calculate the Torque for Each Joint

The torque at each joint depends on the distance ( r ) from the pivot point and the load acting on it.

1. Joint 1 (Base):

This joint supports the entire arm (the weight of the hanging object plus the arms).
The torque at the first joint is:


![image](https://github.com/user-attachments/assets/38717ef4-54cf-48e7-9691-6531c50e4a7e)



Substituting the arm lengths:


![image](https://github.com/user-attachments/assets/fb5693a5-083b-4538-9b09-1122f35628eb)


2. Joint 2 (Middle):

This joint supports the weight of the arms beyond it (second and third arms) plus the hanging weight.



![image](https://github.com/user-attachments/assets/59ed9cba-8ba1-4201-bd43-9c0e156f1e1f)

Substituting the arm lengths:
![image](https://github.com/user-attachments/assets/8c9b1bd9-8f1e-4417-9f67-508bad89fc16)



Step 3: Motor Selection

Based on the calculated torques, the following motors are recommended:

For Joint 1 (Base): Select a motor with a torque rating greater than ( 2.845 Nm ).
For Joint 2 (Middle): Select a motor with a torque rating greater than ( 1.375 Nm ).
For Joint 3 (End-Effector): Select a motor with a torque rating greater than ( 0.392 Nm ).


Suggested Servo Motors:

For Joint 3: Consider the MG996R Servo Motor, which offers a torque of approximately



![image](https://github.com/user-attachments/assets/a9fcf559-61fb-4106-86b7-17e047e8354f)

For Joints 1 and 2: Choose higher-torque motors based on the calculated requirements.
