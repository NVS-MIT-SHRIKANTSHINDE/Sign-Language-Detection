

# Sign Language Detection using Teachable Machine

This project utilizes OpenCV, the cvzone library, and Teachable Machine from Google to recognize hand gestures captured through a webcam and interpret them as sign language. It enables users to capture images of hand gestures representing sign language symbols and save them for training purposes.

## Prerequisites

Before running the code, ensure you have the following dependencies installed:

- Python (3.x recommended)
- OpenCV
- cvzone (install using `pip install cvzone`)
- TensorFlow (for Teachable Machine)
- Teachable Machine (for training and exporting the model)

## Installation

1. Clone this repository to your local machine:

```bash
git https://github.com/NVS-MIT-SHRIKANTSHINDE/Sign-Language-Detection.git
```

2. Install the required Python dependencies:

```bash
pip install -r requirements.txt
```

## Usage

1. Run the main Python script `sign_language_detection.py`:

```bash
python sign_language_detection.py
```

2. Place your hand in front of the webcam to capture images of hand gestures representing sign language symbols.
3. Press the "s" key to save the captured images to the specified folder.
4. Use Teachable Machine to train a model using the saved images.
5. Export the trained model and replace `Model/keras_model.h5` with the exported model file.
6. Adjust the `Model/labels.txt` file with the appropriate labels used during training.

## Folder Structure

- **Data**: Folder to store captured images of hand gestures representing sign language symbols.
- **Model**: Contains the pre-trained model file (`keras_model.h5`) and label file (`labels.txt`).

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for improvements, please create an issue or submit a pull request.


---
