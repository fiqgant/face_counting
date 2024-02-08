# Real-time Face Counting

This project is a real-time face counting application developed in Python, utilizing OpenCV and Streamlit. The application offers face detection and counting functionality, supporting both image and webcam sources.

## Features

- **Image Mode:** Upload an image and adjust scale factor and minimum neighbors to enhance face detection accuracy.
- **Webcam Mode:** Real-time face counting through the webcam with adjustable parameters.
- **Download Results:** Download the processed image with highlighted faces.

## Requirements

- Python 3.6 or later
- OpenCV
- Streamlit
- Pillow
- numpy

## Installation

```bash
pip install opencv-contrib-python Pillow numpy streamlit-webrtc streamlit
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/fiqgant/face_counting.git
cd real-time-face-counting
```

2. Run the application:

```bash
streamlit run main.py
```

3. Open the provided URL in your web browser.

## How to Contribute

If you'd like to contribute to this project, feel free to fork the repository and submit pull requests.

## License

This project is licensed under the [MIT License](LICENSE).