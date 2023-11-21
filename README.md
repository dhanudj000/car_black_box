# car_black_box

Car black box is a device which store the speed time and events of the car.

It is also used to the display the current speed and event of the  car.

This project involves displaying three different screens

# 1.Dashboard

It shows the current time speed and event of the car.

The changes in the events wll be stored into the eeprom.

![Screenshot (75)](https://github.com/dhanudj000/car_black_box/assets/122971572/cc84629c-852d-44fa-b332-1d38fdc50ff5)

# 2.Login screen

It acts as the gate to access the data.

Password need to be entered correctly in 3 attempts to go to next screen

![Screenshot (76)](https://github.com/dhanudj000/car_black_box/assets/122971572/843569fc-266e-438f-b4c9-e7c88b965493)

# 3.Menu screen

It contains different options :

view log         : it prints the data of eeprom in the clcd

clear log        : it clears the eeprom data by loadinf it with 1's

download log     : it transfers data through the uart protocol

change password  : it changes the pswd and writes it into the eeprom

set time         : it helps to write time into RTC.

![Screenshot (77)](https://github.com/dhanudj000/car_black_box/assets/122971572/558e5a86-f6bd-429d-a8fe-3b2904c849ed)

# Technologies used

EMBEDDED C

MPLAB X IDE

PICSIMLAB

TERATERM

HHD VIRTUAL SERIAL CONNECTION
