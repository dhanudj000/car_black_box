# car_black_box

Car black box is a device which store the speed time and events of the car.

it is also used to the display the current speed and event of the  car.

This project involves displaying three different screens

# 1.Dashboard

it shows the current time speed and event of the car.

the changes in the events wll be stored into the eeprom.

https://github.com/dhanudj000/car_black_box/assets/122971572/524801b8-bff3-4276-8b41-0f5c326f8023

# 2.Login screen

it acts as the gate to access the data.

password need to be entered correctly in 3 attempts to go to next screen

![Screenshot (76)](https://github.com/dhanudj000/car_black_box/assets/122971572/843569fc-266e-438f-b4c9-e7c88b965493)

# 3.Menu screen

it contains different options :

view log         : it prints the data of eeprom in the clcd

clear log        : it clears the eeprom data by loadinf it with 1's

download log     : it transfers data through the uart protocol

change password  : it changes the pswd and writes it into the eeprom

set time         : it helps to write time into RTC.

# Technologies used

EMBEDDED C

MPLAB X IDE

PICSIMLAB

TERATERM

HTTP VIRTUAL SERIAL CONNECTION

# Output
