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
  
