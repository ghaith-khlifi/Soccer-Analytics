# Football Analysis Project

## Introduction
This project leverages advanced machine learning techniques to analyze football matches through video footage. Our goal is to detect and track players, referees, and footballs using YOLO, one of the most effective AI object detection models. We will enhance the model's accuracy with additional training.
![Screenshot](output_videos/screenshot.png)

### Features
- **Team Assignment**: Utilizing Kmeans for pixel segmentation and clustering to determine players' team affiliations based on their jersey colors.
- **Ball Possession Analysis**: Analyzing ball possession percentages using team data.
- **Motion Analysis**: Employing optical flow to measure camera movement between frames, aiding in accurate player tracking.
- **Spatial Analysis**: Implementing perspective transformation to represent scene depth and perspective, enabling measurement of player movement in meters.
- **Performance Metrics**: Calculating each player's speed and distance covered during the game.

This project is designed to improve the understanding of game dynamics and serves as a practical application for both beginners and experienced machine learning engineers.

## Modules Used
- **YOLO**: For AI object detection.
- **Kmeans**: For pixel segmentation and clustering based on t-shirt colors.
- **Optical Flow**: For measuring camera movement.
- **Perspective Transformation**: For representing scene depth and perspective.
- **Speed and Distance Calculations**: For tracking player performance metrics.

## Trained Models
- **Trained YOLO v5**: Fine-tuned for detecting football-related objects and activities.

## Sample Video
- **Sample Input Video**: Demonstrates the expected format and content for input videos.

## Requirements
To run this project, the following installations are required:
- **Python 3.x**
- **ultralytics**: For YOLO model implementations.
- **supervision**: Check if this is the correct library or if it was meant to be another name.
- **OpenCV**: For video processing and optical flow calculations.
- **NumPy**: For numerical operations.
- **Matplotlib**: For plotting and visualization.
- **Pandas**: For data manipulation and analysis.

## Installation
To set up the project environment:
```bash
pip install numpy opencv-python matplotlib pandas
pip install ultralytics
# Replace 'supervision' with the correct library if applicable



