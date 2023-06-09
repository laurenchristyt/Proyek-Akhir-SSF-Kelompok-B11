# Proyek-Akhir-SSF-Kelompok-B11 (Air Quality Monitor)

A smart home air quality monitor using Arduino and assembly language that helps users monitor the air quality in their living spaces. The system will use DHT-11 to detect humidity and MQ2 gas sensor to measure various air quality parameters such as temperature, humidity, and air pollutants, especially smoke. It will display real-time air quality data on the MAX7219 and provide alerts with a provided buzzer when the air quality exceeds predefined thresholds.

## Software 
Arduino IDE -> utilized to compile and upload the program onto the Arduino board through a USB type B cable.
Proteus -> utilized to simulate and verify the circuit design.
AVR Assembly -> The program is entirely coded in AVR Assembly language and has been developed and solely tested on the Arduino UNO R3 board with the ATMega328p processor.

## How To Use 
To get started with the Air Quality Monitor project, follow these steps:

1. Connect all the required hardware as shown in the flowchart
2. Clone the repository using the command: 
>git clone https://github.com/laurenchristyt/Proyek-Akhir-SSF-Kelompok-B11.git
3. Open the "Proyek-Akhir-SSF-Kelompok-11" folder using the Arduino IDE.
4. Connect the Arduino board to your computer using a USB type A to type B cable.
5. Check the COM port (Windows) or /dev/ttyUSB0 (Ubuntu) to confirm that the board has been successfully connected.
6. Set the board type to Arduino UNO.
7. Finally, upload the code by clicking on the arrow key icon next to the checklist icon.

## Hardware

### 1. Arduino UNO R3
 A microcontroller board based on the ATmega328P that provides digital and analog I/O pins and can be programmed to control various electronic devices. The Arduino board will be used to control the entire system. 
![image](https://github.com/laurenchristyt/Proyek-Akhir-SSF-Kelompok-B11/assets/113244831/1b8f3e84-63e0-48c1-8061-685df2be2632)
### 2. MAX7219
A chip that can drive up to 64 individual LEDs or an 8x8 LED matrix, commonly used to display text or graphics. The temperature and humidity values will be displayed on this LED matrix.
![image](https://github.com/laurenchristyt/Proyek-Akhir-SSF-Kelompok-B11/assets/113244831/b6238367-60bd-415d-b45f-62ac2e02af4b)
### 3. MQ2 Gas Sensor
A sensor that detects various gases such as smoke, propane, and methane and provides an analog output voltage that can be used to determine the concentration of the detected gas.
![image](https://github.com/laurenchristyt/Proyek-Akhir-SSF-Kelompok-B11/assets/113244831/b23a0cf7-3ec6-4c34-bcb5-6dfcabe0fe76)
### 4. DHT11
A sensor that measures temperature and humidity and provides a digital signal output. The temperature and humidity values will be displayed on the LED matrix.
![image](https://github.com/laurenchristyt/Proyek-Akhir-SSF-Kelompok-B11/assets/113244831/96db6458-5462-4662-8d55-314315a3fd93)
### 5. TMB12A05
A buzzer that produces an audible sound when an electric signal is applied to it, commonly used for alarms or notifications. The buzzer will be used to alert the user when the air quality exceeds the predefined thresholds.
![image](https://github.com/laurenchristyt/Proyek-Akhir-SSF-Kelompok-B11/assets/113244831/20ccb991-a330-416a-8f24-a502e5c3d8d2)

