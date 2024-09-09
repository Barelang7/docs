# Instalasi Software

## Computer Setup
OrangePI 3B

# OS Instalation
## Prepare the required for sintalation
1. TF card, class 10 or above high-speed SanDisk/SamsungEvo card with a minimum capacity of 32Gb (Recomended 64 GB).
2. TF card reader, used to burn the image into the TF card.
3. Monitor/ Display with HDMI Interface.
4. HDMI to HDMI Cable.
5. Power adapter, Orange Pi 3B is recommended to use 5V/3A Type-C power supply for
power supply.
6. Mouse and keyboard with USB interface for development orangepi.
7. 5V cooling fan as a board cooler

## Instalation
How to install OS and GPIO OrangepI 3B can be read in [OrangePI 3B manual book](https://drive.google.com/file/d/1i479ucxErqjL0GDakb5Bw85ptgnDf_Sc/view?usp=drive_link), please follow the instructions carefully.

## setting time with the current time
run the command below at terminal (Ctrl+Alt+T) to adjust the time "yyyy-mm-dd hh:mm:ss"
```
sudo timedatectl set-time "2024-04-12 09:50:00"
```

## Update System
run the command below at terminal (Ctrl+Alt+T) to update and upgrade system
```
sudo apt update
sudo apt upgrade
```

## Instal Terminator
split horizontally, split vertically, etc, on the terminal as one in a single window.
```
sudo apt install -y terminator
```
# Getting the Code Release up and Running

## Installing Dependencies
you need to install the dependencies: the software/libraries required to compile/run the Barelang7 code.
run the following command in the terminal (Ctrl+Alt+T) one at a time:
```
sudo apt-get install libncurses5-dev screen
sudo apt-get install build-essential wget subversion cmake swig libreadline6-dev g++ lua5.1
```
## Download and Install Boots Library
```
mkdir Libraries_Barelang7
cd Libraries_Barelang7
```
Download the latest version of boost from [Here](https://www.boost.org/) (In this case boost_1_84_0.tar.gz). Copy the archive onto the robot directory. Make sure you are in the correct directory of the Robot (Libraries_Barelang7)
```
tar -xvf boost_1_84_0.tar.gz
sudo mv boost_1_84_0 /usr/local/
cd /usr/local/include
sudo ln -s /usr/local/boost_1_84_0/boost boost 
cd -
```

