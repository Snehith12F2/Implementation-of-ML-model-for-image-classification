# Implementation-of-ML-model-for-image-classification
This project uses CNN and machine learning models for image classification. It allows users to upload images, which are processed and classified using deep learning techniques, demonstrating the power of CNNs in image recognition tasks.

## Key Features

**Dual Model Support**:
**MobileNetV2 (ImageNet)**: Capable of recognizing 1,000 different classes from the ImageNet dataset, covering a wide range of objects, animals, and vehicles.
**Custom CIFAR-10 Model**: Designed to classify images into one of ten distinct categories, including airplanes, automobiles, and birds.

**User-Friendly Interface**:
**Navigation Bar**: Easily toggle between the MobileNetV2 and CIFAR-10 models through a streamlined sidebar menu.
**Instant Classification**: Upload images for real-time predictions, complete with confidence scores.

**Educational and Practical Applications**:
 - Perfect for understanding deep learning models and assessing their performance.
 - Valuable for real-world image classification tasks.



## Getting Started

### Prerequisites

- Python 3.7 or later
- A web browser

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/JayRathod341997/DeepLensX.git
   cd Implementation-of-ML-model-for-image-classification
2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
4. **Start the Streamlit app**:
    ```bash
    streamlit run app.py
5. **Open the app**: 
    The app will open in your default web browser. If not, navigate to http://localhost:8501

### Contributing
  Feel free to fork the repository, open issues, or submit pull requests to contribute to the project.

### Acknowledgements
  - Streamlit
  - TensorFlow
