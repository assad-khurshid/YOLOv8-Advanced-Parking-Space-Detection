# YOLOv8 Advanced Parking Space Detection

This project implements a real-time parking space detection system using the YOLOv8 model. The system is designed to identify and monitor available parking spaces in various environments. This can be useful for smart parking solutions, urban management, and optimizing parking lot usage.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project utilizes the YOLOv8 (You Only Look Once) detection model, which has been trained on a custom dataset to accurately identify parking spaces. The model relies on pretrained weights to speed up the training process and improve the detection accuracy.

![YOLOv8 Model Diagram](https://github.com/assad-khurshid/YOLOv8-Advanced-Parking-Space-Detection/blob/main/image-1.png)


## Features

- **Real-Time Detection**: Detects available and occupied parking spaces from live video feeds.
- **Custom Model Training**: Trained using YOLOv8 with a custom dataset specific to parking spaces.
- **Easy Integration**: Can be integrated with existing parking management systems.

## Installation

### Prerequisites

- Python 3.8
- Anaconda3 Navigator
- YOLOv8
- Virtual environment (optional but recommended)

### Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/yolov8-advance-parkingspace-detection-main.git
   cd yolov8-advance-parkingspace-detection-main
   ```

2. **Set Up the Environment**:
   ```bash
   conda create --name parking-detection python=3.11
   conda activate parking-detection
   ```

3. **Install Required Libraries**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application**:
   ```bash
   python app.py
   ```

## Usage

1. Access the application through the command line or integrated user interface.
2. Load a video feed or use a live camera to detect parking spaces.
3. The system will highlight available and occupied parking spaces in real-time.

## Methodology

![YOLOv8 Model Diagram](https://github.com/assad-khurshid/YOLOv8-Advanced-Parking-Space-Detection/blob/main/image-2.png)

### Basic Detection Model

The core of the system is the YOLOv8 detection model. This model has been trained on a custom dataset and leverages pretrained weights to enhance performance. The model is specifically designed for parking space detection and can accurately classify available and occupied spots.

### Model Design

The YOLOv8 model architecture has been modified and trained with custom parameters to improve detection in various lighting conditions and environments.

## Technologies Used

- **Anaconda3 Navigator**: Used for development and debugging.
- **Python 3.8**: Programming language and interpreter.
- **YOLOv8**: Primary detection model for parking spaces.
- **Flask (optional)**: To build a user interface for the application.

## Contributing

Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request.
