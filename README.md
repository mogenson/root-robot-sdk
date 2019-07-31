# PyRoot
Python control of Root Robot via BLE

Open Source Licence: BSD

This example will allow you to control a Root Robot via Python on a Bluetooth-equipped Raspberry Pi (or any other Linux computer with Bluetooth). 


Instructions (from the Linux command line): 

1) Install Gatt-Python by following the instructions here: https://github.com/getsenic/gatt-python
2) If you're using a RasperryPi 3 or Zero W, you've already got Bluetooth Low Energy (BLE) built in, along with the necessary BlueZ library. If not, follow the Gatt instructions: https://github.com/getsenic/gatt-python
3) Clone this repo into your Gatt-Python folder: "git clone https://github.com/shamlian/PyRoot.git"
4) Run the example by typing "Python3 drive-root.py" and then, after it finds your Root, typing in command letters followed by the enter key

"l" = Left
"r" = Right
"f" = Forward
"b" = Back
"s" = Stop
"t" = Turn (input angle)
"u" = Pen Up
"d" = Pen Down
"q" = Quit

It will also display sensor data from the Root (such as touch and bumper sensors) when they are triggered. 

The full Root API is here, if you want to add to this: https://github.com/RootRobotics/root-robot-ble-protocol

Thanks to https://github.com/zlite for the original library, and to https://github.com/mogenson for his original work!
