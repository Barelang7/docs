# Tutorial 

## 1. Tutorial Connect Bluetooth


## 2. Tutorial Running the Robot

1. Turn on the Orange Pi 3B.
2. Connect Orange Pi 3B and PC or Laptop in the same Wi-Fi network.
3. Open NoMachine and wait until Orange Pi 3B shows up on the screen.
 4. After the Orange Pi 3B show in screen NoMachine, click to inside Orange Pi 3B. 
   
***Note:***

***-  if “Orange Pi 3B” does't appear, click “Search again” in the upper right corner of NoMachine,and then no machine will search again to find “Orange Pi3B”,***

***- If “Orange Pi 3B” is not visible, try to connect it using an ethernet cable plugged into the Orange Pi robot and laptop, then re-open NoMachine.***



### Open Terminal in Orange Pi 3B
  - If it has entered into orange pi 3b, open the terminal by click icon “Application” in the upper left corner, then select and click “Terminal Emulator”. 
  - Once the terminal appears, follow these steps and type on the terminal to go the robot program:
  
  ***Into the document directory***
```
~$ cd Documents
```
  ***Into the robot program directory (the robot used is robot 1)***
```
~$ cd Program B7_v1_R1
```
  ***Into the player directory***
```
~$ cd Player
```

### Running the Program
- Before running the program, turn on servo first by press "switch on" on the back's robot
- Make sure all the LED servo on the robot are lit as indicator of servo on.
- Then, running program for the run robot with type in terminal:
```
~$ sudo python3 activate_button.py
```

**There are 3 mini button and an LCD OLED on the robot's back:**

- DCM button on the right.
- MainOP button on the middle.
- IMU button on the left.

following step to press button:

1. First, push the DCM Button on the robot's back.
2. Secondly, press the Main OP Button.
3. Last, press the button IMU.
   
***After pressing each button, OLED screen will display information that the program is running***

### Running the Robot

  - To start running the robot, press the white button located on the shoulder of the robot, then robot will be in initial positition.
  - Last, press again white button on the shoulder of the robot, then robot will be start dancing.

## **3. Tutorial Tunning Robot**

1. Turn on the Orange Pi 3B.
2. Open emulator terminal contained in tab application GUI Orange Pi.
3. After the terminal is opened, can go to directory to run the program ``run_dcm.lua`` by running this syntax:
    ```
    ~$ cd /Document/Program_B7_R1/Player
    ```
    In this section is Robot 1 (R1). Then, click enter.

4. Successfully move to the directory for running the program ``run_dcm.lua``.
5. Before run the program ``run_dcm.lua`` must on servo first by pressing the on swith on the back of robot.
6. After the switch is on, the servo will turn on led synchronously indicating that all servos are active.
7. Next, can run the program ``run_dcm.lua`` by running this syntax: 
    ```
    ~$ lua run_dcm.lua
    ```
    Then, click enter.
8. If run the program is successfully, U2D2 will indicator display a green color (Tx) and blue color (Rx) indicating that the program is running well. 
9.  Open the terminal for running the program ``run_setup.lua``.
10. Move to the directory for running the program ``run_setup.lua`` by running this syntax:
    
    ```
    ~$ cd /Document/Program_B7_R1/Player
    ```
    Then, click enter.
11. Successfully move to the directory for running the program ``run_setup.lua`` by running this syntax:
    
    ```
    ~$ lua run_setup.lua
    ``` 
    Then, click enter.
12. After the program is running, make a robot in a standing position by clicking: 
**v (set the servo position at point 0), b (enable test_walk), 8 (stand)**
13. Next, click **9 (walk)** in the keyboard to see the robot walking in place because the velocity is 0.
14. To make the robot walks forward, click **ii** on the keyboard for add the velocity in the robot.
14. If the robot can't walk properly or robot foot stomps, can the robot tunning by click **v** on the keyboard to make standing upright the robot position on the servo in point 0.
15. Then, make the adjustment to the joints of the robot by adjusting the:
1 and 2 (changing the joint points)
a and d (adding and subtracting values at the right foot joint)
w and x (adding and subtracting values at the left foot joint). The joints that are set are:
    - angkle_pitch,
    - angkle_roll,
    - knee_pitch,
    - hip_pitch,
    - hip_roll,
    - hip_yaw

    according to the robot's needs.

  
