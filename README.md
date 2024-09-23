# Tennis-Analysis-AI

This project showcases how to develop a tennis analysis system using state-of-the-art Machine Learning (ML), Deep Learning (DL), and Computer Vision techniques. It features object detection with YOLOv8, object tracking, and key point detection using a custom Convolutional Neural Network (CNN).

## Features
- **Object Detection:** Detect players and tennis balls using YOLOv8.
- **Custom CNN:** Train a CNN using PyTorch to detect court key points.
- **Object Tracking:** Track players and tennis balls across video frames using object trackers.
- **Data-Driven Features:** Analyze detection data and extract actionable insights.
- **Video Manipulation:** Use OpenCV to read, manipulate, and save video files.

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/Tennis-Analysis-AI.git
    cd Tennis-Analysis-AI
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Object Detection:**
   - Detect players and tennis balls using YOLOv8 from Ultralytics.

2. **Custom Key Point Detection:**
   - Train a CNN in PyTorch to detect court key points for accurate court mapping.

3. **Tracking:**
   - Use object trackers to follow detected objects (players and tennis balls) across frames.

4. **Video Processing:**
   - Utilize OpenCV for reading, processing, and saving video files.

5. **Data Analysis:**
   - Analyze detection data to create features that give insights into player movements and ball trajectory.

## Libraries Used
- [Ultralytics YOLOv8](https://github.com/ultralytics/yolov8)
- [PyTorch](https://pytorch.org/)
- [OpenCV](https://opencv.org/)
- [Object Trackers](https://docs.opencv.org/3.4/d7/d8b/group__video__tracking.html)

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues to improve the project or add new features.

## License

This project is licensed under the MIT License.
