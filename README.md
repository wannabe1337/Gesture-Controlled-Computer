# Gesture-Controlled-Computer
A project using Arduino-Nano, US sensors and Python.

This project is very simple but it will give you many experiences such as working with serial communication, Microcontroller, US Sensor, python and it’s library. To do this project first build the circuit as shown in image below. (I had used Arduino-Nano as a microcontroler.)<br/>

![image](https://user-images.githubusercontent.com/62278793/139541909-0f1e249b-02e4-43c2-9576-0e4d1f96e356.png)

<br/>Once you build the circuit, connect the Arduino to PC, select the board and port (If port is not showing -- just install https://sparks.gogo.co.nz/ch340.html driver) in Arduino IDE and upload the 'ReadUS' program to Arduino.</>

The "ReadUS" program measures the distance between the hands and Sensor and sends the 'Message' accordingly to serial port.<br/>

Now edit the COM-Port in python program according to yours and execute it. It will continuously look for message at specified port and sends control signals to the syatem accordingly.

Just edit the program as per your need and enjoy the feeling of a SUPER-HUMAN :)
