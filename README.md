# Face Mask Detection using Convolutional Neural Network (CNN)

## Overview

This project demonstrates a face mask detection system using Convolutional Neural Networks (CNNs) to classify whether a person is wearing a mask or not. The system is designed to enhance safety and health measures by automating the detection of face masks in real-time. The CNN model is trained on a dataset of images with and without face masks, achieving high accuracy in distinguishing between the two classes.

## Features

- **Real-Time Detection**: Detects face masks from live camera feeds or video files.
- **High Accuracy**: Utilizes a well-designed CNN architecture to achieve high classification accuracy.
- **User-Friendly Interface**: Simple command-line interface for running the model and analyzing results.
- **Pre-trained Model**: Includes a pre-trained model for ease of use.

## Technologies

- **Python**: Programming language used for developing the application.
- **TensorFlow/Keras**: Deep learning frameworks used to build and train the CNN model.
- **OpenCV**: Library for real-time computer vision tasks, including image and video processing.
- **NumPy**: Library for numerical computations.
- **Matplotlib**: Library for plotting and visualizing data.

## Installation

To set up the project, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/face-mask-detection.git
   cd face-mask-detection
   ```

2. **Download the Dataset**:
   Download the dataset from [(https://www.kaggle.com/datasets/omkargurav/face-mask-dataset/code)] and place it in the `data/` directory.

## Usage

- **Training the Model**: Customize training parameters and epochs in `train.py`. Ensure your dataset is correctly placed and formatted.
- **Running Detection**: Use `detect.py` to analyze video streams or files. Adjust parameters as needed for optimal performance.

## Contributing

Contributions are welcome! To contribute to the project, please fork the repository, make your changes, and submit a pull request. For major changes, please open an issue to discuss what you would like to change.
