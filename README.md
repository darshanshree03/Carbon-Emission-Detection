# Carbon Emission Tracking System 🚗🌱

An ESP32-based vehicle emission monitoring prototype developed during a hackathon, combining gas sensors and machine learning to explore vehicle emission analysis and environmentally conscious driving.

## Overview

Vehicle emissions contribute to air pollution and environmental degradation. This project explores a system for monitoring gas levels using an ESP32 and gas sensors, with the goal of providing insights into vehicle emissions and encouraging eco-friendly driving practices.

The project was developed as part of the DeCarbonizers team for the iCube 4.0 hackathon at Sri Venkateswara College of Engineering.

## System Architecture

The proposed system consists of four main components:

1. **Sensor layer:** Gas sensors connected to an ESP32 for collecting sensor readings.
2. **Data processing:** Collection and preparation of sensor data for analysis.
3. **Machine learning:** An LSTM-based approach explored for emission prediction.
4. **User interface:** A proposed interface for presenting emission information and driving-related insights.

## Hardware Components

- ESP32 development board
- MQ2 gas sensor
- MQ7 gas sensor
- MQ135 gas sensor
- 9V battery and voltage regulation circuitry
- Push button
- Breadboard and connecting wires

## Machine Learning

The project includes a Google Colab notebook exploring an LSTM-based model for emission prediction.

The notebook covers machine learning workflows such as data preprocessing, feature scaling, model training, and prediction.

**Dataset:** The original dataset used by the notebook is being located. Reproducing the complete workflow may require access to the original dataset and adjustment of the notebook's data-loading paths.

## Hardware Demonstration

The project includes a physical hardware prototype using an ESP32 and gas sensors.

See the `images/` directory for hardware photographs and system diagrams.

## Repository Structure

```text
Carbon-Emission-Tracking-System/
├── README.md
├── requirements.txt
├── notebooks/
│   └── Decarbonizers1.ipynb
├── docs/
│   └── hackathon_presentation.pdf
└── images/
    ├── hardware_prototype.jpg
    └── architecture_diagram.png
```

## Current Status and Limitations

- Hardware prototype demonstrated during the project.
- Machine learning experimentation documented in the Colab notebook.
- Original dataset availability is being checked.
- The original backend implementation is currently unavailable.
- End-to-end integration and prediction accuracy have not been independently verified.

This project is a prototype and should not be treated as a calibrated vehicle-emissions measurement system without further testing and validation.

## Future Improvements

- Recover and document the original backend implementation.
- Improve sensor calibration and measurement reliability.
- Validate the prediction model using appropriate datasets and evaluation metrics.
- Integrate the hardware, prediction model, and user interface into a complete system.
- Explore real-time data visualization and eco-driving feedback.

## Project Context

**Team:** DeCarbonizers  
**Institution:** Sri Venkateswara College of Engineering  
**Event:** iCube 4.0 Hackathon

