# Knee Flexion Calculator

This web application allows physiotherapists and medical professionals to measure and track knee flexion angles for patients over time. It uses AI-powered pose detection to calculate knee angles from uploaded images or photos taken directly through the device's camera.
https://bhanu9prakash.github.io/knee-flexion-calculator/
![image](https://github.com/user-attachments/assets/546a9f84-5bc5-4b9d-99ee-58f14a4d5a66)


## Features

- Patient data management
- Image upload or camera capture for knee flexion measurement
- AI-powered pose detection for accurate angle calculation
- Interactive angle adjustment
- Progress tracking with charts
- Responsive design for desktop and mobile use

## Usage

1. Enter the patient's name and select a date.
2. Click "Upload and Adjust Points" to either upload an image or take a photo.
3. Adjust the detected points if necessary for accurate angle calculation.
4. Click "Confirm and Save Angle" to store the measurement.
5. View progress over time in the chart below.

## Technical Details

This application uses:
- TensorFlow.js and PoseNet for pose detection
- Chart.js for data visualization
- Tailwind CSS for styling
- vanilla JavaScript for interactivity

## Setup

To run this project locally:

1. Clone the repository
2. Open `index.html` in a web browser

Note: This application requires an internet connection to load the necessary libraries (TensorFlow.js, Chart.js, etc.).

## License

This project is open source and available under the [MIT License](LICENSE).

