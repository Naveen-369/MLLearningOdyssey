# Leaf Disease Detection Project

## Overview
The Leaf Disease Detection project is designed to identify various plant leaf diseases using advanced machine learning techniques. This project can detect diseases in the leaves of various plants, including but not limited to grape and tomato plants. The model used in this project is based on EfficientNet and achieves an accuracy of over 90%. It has been trained with a dataset containing more than 50,000 images.

## Features
- **Multiple Plant Support:** Detects diseases in the leaves of various plants, such as grape and tomato.
- **High Accuracy:** The model achieves an accuracy of over 90%, ensuring reliable disease detection.
- **Large Dataset:** Trained with a robust dataset containing over 50,000 images, enhancing the model's performance and generalization capabilities.

## Model
The project utilizes the EfficientNet model, known for its efficiency and accuracy in image classification tasks. EfficientNet scales the network width, depth, and resolution in a balanced manner to achieve better performance.

## Dataset
The dataset comprises over 50,000 images of healthy and diseased leaves from various plants. This extensive dataset allows the model to learn and generalize well to different types of diseases and plant species.

## Requirements
To run this project, you will need the following:
- Python 3.x
- Jupyter Notebook
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib

You can install the necessary packages using pip:
```bash
pip install jupyterlab tensorflow keras opencv-python numpy pandas matplotlib
```
## Usage
### 1. Clone the Repository:
```bash
git clone https://github.com/yourusername/leaf-disease-detection.git
cd leaf-disease-detection
```
### 2. Prepare the Dataset:
Ensure that your dataset is organized in the following structure:
```bash
dataset/
├── train/
│   ├── class1/
│   ├── class2/
│   └── ...
├── validation/
│   ├── class1/
│   ├── class2/
│   └── ...
└── test/
    ├── class1/
    ├── class2/
    └── ...
```
### Run the jupyter Notebook
Open the Jupyter Notebook and run the cells to execute the code.
```bash
jupyter notebook leaf_disease_detection.ipynb
```

## Contribution
Contributions are welcome! Please submit a pull request or open an issue to discuss improvements, bug fixes, or new features.

## License
This project is licensed under the MIT License. See the `LICENSE` file in the root directory for more details.

## Acknowledgements
-  The creators of the EfficientNet model.
-  The contributors of the [dataset](https://www.kaggle.com/datasets/naveenkumar3690/ready-leaf-disease-detection-dataset) used for training the model.
