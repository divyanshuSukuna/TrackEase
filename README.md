# RFID-Based Attendance System
## Overview

This project is an RFID-based attendance system designed using Arduino Uno. It enables automatic recording of attendance for various institutions such as schools, companies, and corporate environments. The system utilizes RFID tags and readers to track attendance and logs the data into an Excel sheet for easy management.


## Components Used

- **Arduino Uno**: Main microcontroller board for processing data.
- **RFID Reader (MFRC522)**: Reads RFID tags/cards.
- **RFID Tags/Cards**: Used by individuals for attendance.
- **Breadboard**: For prototyping and connecting components.
- **Jumper Wires**: For making electrical connections.
- **Buzzer**: Provides audible feedback.
- **Resistors**: For proper functioning of electronic components.
- **Push Buttons**: (Optional) For additional controls.

## Features

- **RFID-Based Identification**: Unique identification of individuals using RFID tags/cards.
- **Automatic Attendance Logging**: Records attendance data in an Excel sheet.
- **Audible Feedback**: Buzzer provides feedback on successful or failed scans.
- **Easy Setup and Integration**: Suitable for various institutional environments.

## Setup and Installation

### Hardware Setup

1. Connect the RFID reader to the Arduino Uno as per the wiring diagram.
2. Connect the buzzer and any optional components like push buttons to the Arduino.
3. Ensure all connections are secure on the breadboard.

### Software Installation

1. **Install Arduino IDE**: Download from [Arduino's official website](https://www.arduino.cc/en/software).
2. **Install Required Libraries**:
   - **MFRC522 Library**: Install via Library Manager or download from [GitHub](https://github.com/miguelbalboa/rfid).
3. **Upload Code**:
   - Open the provided Arduino sketch in the Arduino IDE.
   - Connect your Arduino Uno to your computer and upload the code.

### Excel Integration

1. **Serial-to-Excel Bridge**: Use tools like [PLX-DAQ](https://www.practicalmaker.com/plx-daq) to bridge serial data to Excel.
2. **Configuration**: Set up the bridge to capture and log data from the Arduino’s serial output.

