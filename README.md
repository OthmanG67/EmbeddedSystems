# EmbeddedSystems
This project is a **Smart Home Device Manager** developed using an Arduino and an Adafruit RGB LCD Shield. It allows users to manage and control smart home devices through serial commands and button inputs. The system uses a Finite State Machine (FSM) to navigate between states such as synchronization, device registration, and interaction through the physical LCD buttons.

## Features

- **Serial Communication Interface** for adding, updating, and removing smart devices.
- **Device Management**: Add new devices with unique IDs, types, and locations.
- **State Control**: Turn devices on/off and update temperature or power settings.
- **Button-Based Navigation**:
  - Scroll through registered devices using UP and DOWN buttons.
  - View only OFF devices with LEFT button.
  - Show student ID and system RAM status by holding SELECT button for 1+ seconds.
- **Finite State Machine (FSM)** implemented for smooth transition between modes (SYNC and MAIN).
- **Real-Time LCD Feedback** using Adafruit RGB LCD
