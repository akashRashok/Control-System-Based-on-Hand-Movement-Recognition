# Control System Based on Hand Movement Recognition

This project implements a cost-effective, real-time hand movement recognition control system using an RGB camera. It's designed to provide a more accessible alternative to high-cost systems, utilizing Python and Unity for gesture recognition and visualization.

## Key Features

- **Gesture Recognition**: Utilize the MediaPipe library to detect hand gestures with high fidelity.
- **Gesture Mapping**: Map recognized gestures to specific commands using JSON files.
- **Command Execution**: Execute actions mapped to recognized gestures with minimal delay.
- **Visualization**: Display recognized gestures and their corresponding actions using Unity.

## System Architecture

The control system operates through a software interface that processes inputs from an RGB camera placed before the user. Gestures are recognized, mapped to commands, and visualized in real time, ensuring a seamless user experience.
![Architecture](https://github.com/akashRashok/Control-System-Based-on-Hand-Movement-Recognition/assets/57842319/9f7058d4-988b-48ea-821c-00cd024b69d5)



## Getting Started

### Prerequisites

- Python 3.x
- Unity
- MediaPipe
- PySimpleGUI (for the control software GUI)

### Installation

1. Clone the repository
2. Install the required Python libraries:
pip install mediapipe opencv-python pysimplegui

### Usage

1. Run the control software: Control_system.exe
2. Perform gestures in front of the RGB camera.
3. Use the GUI to remap gestures and actions if necessary.

## Performance

The system achieves an average of 30 FPS across various hardware setups and demonstrates a gesture recognition accuracy of 90.2% under diverse lighting conditions.

## Future Scope

- Expand the system to detect more complex gestures using both hands.
- Explore applications in various fields such as healthcare, engineering, and entertainment.

## Contributors

- [Akash Renuka Ashok](https://github.com/akashRashok)
- Gokul S
- John Paul
- Kevin Joe Sebastin


## Acknowledgments

- Thanks to MediaPipe for the robust hand-tracking models.
- Special thanks to all contributors and testers of the project.
