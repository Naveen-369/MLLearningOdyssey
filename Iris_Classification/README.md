<h1 style="text-align:center;font-size:39px">Iris Classification Project</h1>

## Overview
The Iris Classification project is designed to classify iris flowers into three unique species based on the length and width of their sepals and petals. The dataset contains 151 entries. The categorical data has been converted into numerical format using one-hot encoding. The model employs a logistic classifier to predict the species of iris flowers, achieving an accuracy of 97.77%.

## Features
- **Classification:** Predicts the species of iris flowers based on sepal and petal measurements.
- **High Accuracy:** The model achieves an accuracy of 97.77%.
- **One-Hot Encoding:** Converts categorical data into numerical format for better model performance.

## Dataset
The dataset contains 151 entries with the following features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species (target variable with 3 unique classes)

## Model
The project uses a logistic classifier, which is a robust and widely-used method for classification tasks. The model has been trained and tested on the dataset, resulting in a high accuracy of 97.77%.

## Requirements
To run this project, you will need the following:
- Python 3.x
- Jupyter Notebook
- pandas
- scikit-learn

You can install the necessary packages using pip:
```bash
pip install jupyterlab pandas scikit-learn
```

## Usage
### 1. Clone the Repository :
```bash
git clone https://github.com/Naveen-369/MLLearningOdyssey
cd iris-classification
```
### 2. Run the Jupyter Notebook :
Open the Jupyter Notebook and run the cells to execute the code.
``First Time``:Run all the cells in the Jupyter Notebook
```bash
jupyter notebook iris_classification.ipynb
```
Once the first run is done, run only the last cell which will get the input and give the cetegorical output.
### 3. Predicting the Flower Species:
Use the declared function to predict the species of iris flowers based on sepal and petal measurements. The function `FindFlower()` will be called with the input parameters (sepal length, sepal width, petal length, petal width) to predict and display the flower type.

## Project Structure 
`iris_classification.ipynb`: Jupyter Notebook containing the code for data preprocessing, model training, evaluation, and prediction.

`data.csv`: CSV file containing the iris dataset.

## Function Input
To predict the species of an iris flower, use the `FindFlower()` function. This function takes the sepal length, sepal width, petal length, and petal width in the form of 2d array as input parameter and returns the predicted species.
```bash
def FindFlower([[sepal_length, sepal_width, petal_length, petal_width]]):
        .
        . // Declaration of the function goes here . . . . .
        .
# Example of function call
FindFlower([[5.1, 3.5, 1.4, 0.2]])
```
## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss improvements, Implementation through an new effecient model, bug fixes, or new features.

## License 
This project is licensed under the MIT License. See the `LICENSE` file in the root directory for more details.
