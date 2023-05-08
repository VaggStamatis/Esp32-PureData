| Build Target | ESP32 DevKitc V4|
| ------------ | --------------- |

# Esp32-PureData
This is a project that combines :
- An ESP32 potentiometer control Project 
- A Pure Data FM Synth Projet 
- The purpose of this project is to control the FM Synth's Carrier Frequency with the potentiometer connected on the ESP32 

# Initializing and Running the Project 
- Run the *.ino* file on the Arduino IDE and upload the code to the ESP32 
- Run the *.pd* File with Pure Data and first click on the `devices` object to get a print ouput of the connected devices 
- Use the printed number next to the ports in the `comport` object in the .pd file 
- Now when the .ino code runs on the ESP32 and we rotate the potentiometer then we must hear a change in the output noise through Pure Data

## _Wiring_of_the_Potentiometer_with_the_ESP32_
Wire the potentiometer to the ESP32 as shown in the picture below. 
You can either use a sliding or a rotating potentiometer
<img src="https://github.com/VaggStamatis/Esp32-PureData/blob/main/esp32%26Pontetiometer.png" width="600">

# Creator 
Evangelos Stamatis: evanstamatis@gmail.com
