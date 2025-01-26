# Bicep Curl Counter with MediaPipe and OpenCV

## Overview
This project is a real-time bicep curl counter built using Python, OpenCV, and MediaPipe. It leverages computer vision and pose estimation to detect body movements and count repetitions of bicep curls. The project can be used for fitness tracking and exercise analysis.

## Features
- **Real-time Video Feed**: Uses your webcam to capture live video.
- **Pose Detection**: MediaPipe is used to detect key points on the body.
- **Bicep Curl Counting**: Detects arm movements to accurately count bicep curls.
- **User-Friendly Interface**: Displays the video feed with visual feedback.

## Technologies Used
- **Python**: The primary programming language.
- **OpenCV**: For video capture and frame processing.
- **MediaPipe**: For pose estimation and drawing utilities.
- **NumPy**: For numerical computations.

## Setup Instructions
### Prerequisites
- Python 3.8 or later
- A webcam connected to your system

### Required Libraries
Install the required Python libraries using pip:
```bash
pip install opencv-python mediapipe numpy
```

### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/rahul-1809/bicep_curl_counter/
   ```
2. Navigate to the project directory:
   ```bash
   cd bicep-curl-counter
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook bicep_curl_counter.ipynb
   ```
4. Run the cells sequentially to execute the program.

## How It Works
1. The program captures the live video feed using OpenCV.
2. MediaPipe processes each frame to detect body landmarks.
3. The arm angle is calculated using the detected landmarks.
4. Based on the arm's movement and angle threshold, the system counts a bicep curl.

## Key Sections in the Notebook
- **Imports**: Includes all necessary libraries for the project.
- **Video Feed Setup**: Captures and displays the live video feed.
- **Pose Detection**: MediaPipe integration for real-time pose estimation.
- **Curl Counting Logic**: Calculates arm angles and counts repetitions.
- **Visualization**: Annotates the video feed with pose landmarks and count.

## Example Output
- A live video feed displaying detected landmarks.
- The current count of bicep curls displayed on the screen.

## Customization
You can customize the project by:
- Adjusting angle thresholds for counting curls.
- Modifying the code to include additional exercises or movements.

## Troubleshooting
- Ensure your webcam is properly connected and accessible.
- Install all dependencies before running the notebook.
- If the pose detection is inaccurate, adjust the camera position and lighting.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.
