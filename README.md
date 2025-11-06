# Rule-Based Driver Drowsiness Detection

## Overview

Driver drowsiness is a major cause of road accidents worldwide. This repository presents a rule-based system for detecting driver drowsiness using computer vision and signal processing techniques. The goal is to provide a non-intrusive methodology that analyzes visual cues such as eye closure, yawning, and head pose to determine the likelihood of driver fatigue.

## Features

- **Eye Closure Detection:** Analyzes blink rates and eye aspect ratios to monitor drowsiness indicators.
- **Yawning Recognition:** Detects mouth movements associated with yawning using facial landmarks.
- **Head Pose Estimation:** Determines head orientation to check for signs of nodding off.
- **Rule-Based Decision System:** Integrates detected features within a logical framework to assess sleepiness risk.
- **Real-Time Processing:** Optimized for live webcam input or recorded videos.
- **Alert System:** Optionally triggers alarms when drowsiness is detected.

## Technologies Used

- Python (OpenCV, NumPy, etc.)
- [Mediapipe](https://google.github.io/mediapipe/) (ML-powered face mesh and landmark detection)
- Computer vision and signal processing techniques
- No explicit deep learning model training; relies on Mediapipe's pretrained models for face/eye/mouth landmark extraction
- [List any other relevant frameworks/libraries as appropriate]

## Getting Started

### Prerequisites

- Python 3.x
- OpenCV (`cv2`)
- mediapipe
- pygame
- NumPy
- [Other dependencies as used in your project]

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/GeekySalami/Rule-Based-Driver-Drowsiness-Detection.git
   cd Rule-Based-Driver-Drowsiness-Detection
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. To run the drowsiness detection system on your webcam:

   ```bash
   python Finale_wth_mndppe.py
   ```

2. For processing a video file:

   ```bash
   python Finale_wth_mndppe.py --video path_to_video.mp4
   ```

3. Configure rule thresholds and parameters in `config.py` as needed.

## Folder Structure

- `Finale_wth_mndppe.py` – Main detection module using Mediapipe.
- `drowsiness/` – (If exists) Core detection modules (eye, mouth, head pose).
- `config.py` – Thresholds and settings for rule-based system.
- `requirements.txt` – Python dependencies.
- `README.md` – Project documentation.

## Demo

Sample demonstration (screenshots/gif/video) of the system in action:
![Demo Screenshot](demo/demo_screenshot.png)

## Contributing

Contributions are welcome! Please fork the repository, submit PRs, or open issues to discuss improvements and bug fixes.

## License

This project is licensed under the MIT License. See `LICENSE` for details.

## Acknowledgements

- [OpenCV](https://opencv.org/)
- [Mediapipe](https://google.github.io/mediapipe/)
- [Any other references]

## Contact

For questions or collaboration opportunities, contact [Your Name or Email].
