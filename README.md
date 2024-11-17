# AR Mobility Assistant for Safe Driving System (ARMASDS) - Prototype

## Project Overview

ARMASDS (Augmented Reality Mobility Assistant for Safe Driving System) is a cutting-edge AR-based system designed to assist drivers in navigating hazardous conditions. This prototype leverages augmented reality to project real-time hazard warnings, navigation instructions, and other critical information directly onto the windshield, helping drivers avoid potential risks and improve situational awareness.

This Unity-based game prototype simulates a driving environment that includes navigation, hazard detection, weather conditions, and speed sign recognition. The system's goal is to enhance road safety by providing immediate feedback and proactive route adjustments for drivers.

## Key Features

- **Customizable AR HUD**: Augmented alerts projected directly onto the windshield for immediate driver action.
- **Smart City Integration**: Connects with infrastructure to receive live updates on road conditions, traffic, and hazards.
- **Dynamic Route Adjustments**: Provides alternate, safer routes based on real-time hazard detection.
- **Real-Time AR Hazard Detection**: Detects potholes, debris, and weather impacts using LiDAR, sensors, and cameras.

## How to run the Prototype

1. Download the **ARMASDS-Prototype** file from this repository.

![image](https://github.com/user-attachments/assets/74b0dadb-2541-453e-8118-3e731c9f6164)

2. Open the **ARMASDS** file to open the prototype.

![image](https://github.com/user-attachments/assets/c524bd6d-2749-4f85-991d-9155a68cee61)

3. Click on the **Car Project** to run the prototype.

![image](https://github.com/user-attachments/assets/bbdcd48d-eff0-48d6-8d85-f3216a89a8e8)

4. Use the arrow keys (or WASD) to control the vehicle and navigate the environment.
5. The game will provide AR-based alerts for hazards like speed signs, potholes, and weather-related obstacles.

## Architecture:
![image](https://github.com/user-attachments/assets/a1f48e36-6527-4095-ab2e-11d0c4e5debc)

At the heart of the ARMASDS architecture is the combination of real-time data collection, processing, and display mechanisms that work in harmony to ensure the driver receives immediate hazard warnings, routing suggestions, and other relevant driving information directly on their AR heads-up display (HUD). The architecture can be broken down into several key stages: Data Collection, Data Processing, Decision Making, and Display/Feedback.

## Data Collection:

**Sensors and Cameras**: The system uses a combination of sensors (such as LiDAR) and cameras mounted on the vehicle to monitor the environment. These sensors capture a range of data, from the car's immediate surroundings to the broader road conditions, including obstacles (potholes, debris) and weather impacts (fog, rain).

**GPS Module**: The GPS provides real-time location and movement data, enabling accurate vehicle positioning. This information is critical for the system's dynamic routing and traffic management features.

**Weather Sensors & Traffic Info**: Additional data inputs from external sources (weather sensors and live traffic data feeds) enable the system to assess driving conditions beyond what the vehicle’s sensors can capture.

## Data Processing:

**Processing & Analysis**: The data collected by the sensors, cameras, and GPS is sent to a central processing unit where it is analyzed using advanced algorithms. The system processes visual data from cameras and LiDAR to identify potential hazards, such as potholes or other road blockages, and analyzes weather data to assess driving conditions.

**Hazard Detection Algorithms**: Using computer vision and machine learning models, the system identifies obstacles and environmental hazards in real-time. These could include stationary obstacles (like debris) or dynamic ones (such as other vehicles or pedestrians). The hazard detection also factors in weather conditions such as fog or rain.

**Dynamic Routing & Traffic Management**: Based on hazard detection and real-time traffic data, the system dynamically adjusts the vehicle’s route to avoid potential dangers. It calculates alternative paths to ensure the safest and quickest route is always taken.

## Decision Making:

**Decision Point (Hazard Detected?)**: A critical decision-making step occurs when the system determines if there is a hazard in the path of the vehicle. If a hazard is detected, the system activates the AR HUD to alert the driver and adjusts the route if necessary. If no hazard is detected, the system continues to monitor the environment and provide standard navigation assistance.

**Cloud Connectivity**: Data collected by the vehicle is sent to the cloud for further analysis and updates, ensuring that the system is continuously learning and adapting. The cloud may also provide additional insights such as live traffic updates and road conditions.

## Display & Feedback:

**Augmented Reality Display**: When a hazard is detected, the system immediately projects warnings or hazard alerts directly onto the windshield in the driver’s field of view using the AR heads-up display. This enables the driver to respond quickly without needing to look away from the road. Information like speed limits, dynamic route guidance, and hazard warnings are displayed contextually over the real-world view.

**Feedback & Alerts**: In addition to visual cues, the system may also provide auditory or haptic feedback for critical alerts (such as sudden obstacles or sharp turns). This helps ensure that the driver is always aware of potential hazards, especially in situations where visual cues might be insufficient.

This detailed architecture provides a holistic view of how ARMASDS functions as an intelligent driving assistant. By leveraging data from multiple sensors, real-time processing, and advanced AR technology, the system aims to significantly reduce the risk of accidents caused by hazardous driving conditions. The seamless integration of these components ensures that drivers receive immediate and actionable information, making driving safer, more intuitive, and less stressful.


## Requirements

- **Unity** (for development and simulation)
- **Windows PC** (for running the executable)
- **AR-enabled hardware** (optional, if implementing on physical devices)

## Future Work

- Implement full AR hazard detection using real sensors.
- Add vehicle detection and dynamic route changes.
- Expand the game with more levels and features related to real-world driving scenarios.

## Installation

1. Download the latest version of the game (ARMASDS.exe).
2. Run the executable on a Windows machine.

## License

The conceptual idea of ARMASDS (AR Mobility Assistant for Safe Driving System) may be used for inspiration and further development; however, all content, including specific implementations, code, designs, and descriptions, is strictly protected and not allowed for copying as it is being used for i.Mobilothon 4.0. Any reproduction or replication of this content without explicit permission is prohibited. Please refer to the LICENSE file for additional details.

This project is licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License. For more details, see the [LICENSE](./LICENSE) file or visit the [Creative Commons website](https://creativecommons.org/licenses/by-nc-nd/4.0/).


## Acknowledgements

- Unity for providing the game engine and tools.
- All assets and contributors to the development of ARMASDS.
