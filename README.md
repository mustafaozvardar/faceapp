# 👤 Real-Time Face Recognition

This is a real-time face recognition application built with Python using the `face_recognition` library and OpenCV. It can recognize and label faces from a video stream captured by your webcam.

## Features ✨

- 📷 Captures video from your webcam in real-time.
- 🧠 Recognizes and labels faces using pre-trained images.
- 🚀 Displays the video feed with recognized faces highlighted and labeled.

## Requirements 📦

- Python 3.x
- `opencv-python` library
- `face_recognition` library
- A working webcam

## Installation 🚀

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/face-recognition-app.git
    cd face-recognition-app
    ```

2. Install the required libraries:

    ```bash
    pip install opencv-python face_recognition
    ```

3. Place the known images in the specified directory:

    - Ensure your images are correctly named and located in the right path as indicated in the script.

## Usage 🎤

1. Prepare your known faces:

    - Store images of the individuals you want to recognize in the designated folder.
    - Update the script with the correct file paths to these images.

2. Run the script:

    ```bash
    python face_recognition_app.py
    ```

3. The application will start capturing video from your webcam. Faces recognized from the known images will be labeled with their names.

4. To stop the application, press the `q` key.

## License 📜
This project is licensed under the MIT License - see the LICENSE file for details.
