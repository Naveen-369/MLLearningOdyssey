# Road Lane Line Detection System

This repository contains a Python-based road lane line detection system using computer vision techniques. The system processes video frames and identifies lane lines, which is essential for applications like autonomous driving and advanced driver assistance systems (ADAS).

## Features

- Detects road lane lines in real-time video streams.
- Utilizes the following techniques:
  - Canny edge detection
  - Hough Line Transform
  - Region of Interest (ROI) masking
- Outputs processed frames with highlighted lane lines.

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/road-lane-detection.git
   cd road-lane-detection
   ```

2. Install the required dependencies (assuming you have Python and pip installed):

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the lane detection system on a video file:

   ```bash
   python lane_detection.py --input test_video.mp4
   ```


2. The processed video will be saved as `output_video.mp4`.


## Lisence

This project is licensed under the MIT License. See the `LICENSE` file for more details.

Feel free to add more sections, such as "Contributing," "References," or "Future Work," depending on your project's scope. Good luck with your road lane line detection system! 🚗🛣️
