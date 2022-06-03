# Robotic-Drawing-Table


-The design of the project is shown in the figure below.

![image](https://user-images.githubusercontent.com/100121000/171878473-ff3fcf1b-7818-486a-9261-2d685672f270.png)


set up:

-Download the [Arduino IDE from Arduino website](https://www.arduino.cc/en/software).

-Download the [GRBL libary from github.com](https://github.com/gnea/grbl). 

1. Open the Arduino IDE, navigate to Sketch > Include Library > Add .ZIP Library…

2. Navigate to the extracted folder “grbl-master”, in there select the “grbl” folder and click the open file. Now we have GRBL as an Arduino Library.

3. Navigate to File > Examples > grbl > grblUpload. Then select the Arduino board and the COM port.

-Download the version 2.0.9. [UGS software form UGS website](https://winder.github.io/ugs_website/). 

1. Open UGS platform, navigate to Machine > Setup wizard, choose the port COM5 and click the Connect button.

2. navigate to File > Open, and open the G-code file crab.ngc.

3. Navigate to Machine > Setup wizard, and modify the step size and other properties of the motors.

4. Run the G-code.



