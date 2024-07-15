![PrevezeROV](/logo.png)
# PrevezeROV

## Description
PrevezeROV is an advanced underwater vehicle project designed for exploration and various underwater tasks. The project involves motor control, sensor integration, communication with a Raspberry Pi, and a torpedo launch system.

## Features
- **Motor Control:** Precise control of thrusters for movement in X, Y, and Z directions.
- **Sensor Integration:** Real-time data acquisition from MPU6050 accelerometer and gyroscope.
- **Torpedo Launch System:** Controlled torpedo launching mechanism with safety features.
- **Camera Control:** Servo-based camera angle adjustment.
- **Communication:** CAN bus communication with Adafruit MCP2515 and serial communication with Raspberry Pi.

## Specifications
- **Microcontroller:** Arduino
- **Thrusters:** 6 Servo Motors
- **Sensors:** MPU6050 Accelerometer and Gyroscope
- **Communication:** CAN bus (Adafruit MCP2515), Serial
- **Torpedo Launchers:** 3 Torpedo launchers with hold and launch mechanisms
- **Power Supply:** Appropriate power supply for underwater operations

## Dependencies and Installation
### Hardware Requirements
- Arduino Board
- Adafruit MCP2515 CAN bus module
- Adafruit MPU6050 sensor
- Servo Motors (6 for thrusters, 1 for camera)
- Torpedo launch mechanism
- Various connectors and wires

### Software Requirements
- Arduino IDE
- Adafruit MCP2515 library
- Adafruit MPU6050 library
- Servo library

### Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/YourUsername/PrevezeROV.git
    cd PrevezeROV
    ```

2. **Install the necessary Arduino libraries:**
    - Open Arduino IDE
    - Go to `Sketch` > `Include Library` > `Manage Libraries...`
    - Search for and install the following libraries:
        - Adafruit MCP2515
        - Adafruit MPU6050
        - Servo

3. **Upload the code to your Arduino:**
    - Connect your Arduino board to your computer.
    - Open `PrevezeROV.ino` in Arduino IDE.
    - Select the correct board and port from `Tools` menu.
    - Click the upload button.

## Repo Tree


## Thanks
We would like to extend our sincere thanks to our sponsors who have supported this project.

[![3D Kafası](https://3dkafasi.com/logo.png)](https://3dkafasi.com/) &nbsp; [![İDÇ Liman İşletmeleri](https://www.idcliman.com.tr/images/logos/idc_resize_white.svg)](https://www.idcliman.com.tr/tr)

Your contributions have been invaluable in making PrevezeROV a reality.

