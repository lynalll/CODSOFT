# Iris Flower Classification

This project implements a machine learning model to classify Iris flowers into three species: Setosa, Versicolor, and Virginica, based on their sepal and petal measurements. The k-Nearest Neighbors (k-NN) algorithm is used for classification, and performance is evaluated using a confusion matrix and accuracy metrics.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [How It Works](#how-it-works)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The Iris dataset is a widely used dataset in the field of machine learning and statistics. It consists of 150 samples of iris flowers, each with four features: sepal length, sepal width, petal length, and petal width. The goal of this project is to build a model that can accurately classify iris flowers into their respective species based on these measurements.

## Dataset
The Iris dataset can be found in the file `IRIS.csv`. The dataset consists of the following columns:
- `sepal_length`: Length of the sepal in centimeters
- `sepal_width`: Width of the sepal in centimeters
- `petal_length`: Length of the petal in centimeters
- `petal_width`: Width of the petal in centimeters
- `species`: The species of the iris flower (Setosa, Versicolor, Virginica)

## Technologies Used
- Python
- Pandas
- Scikit-learn
- Seaborn
- Matplotlib

## How It Works
1. **Data Loading**: The dataset is loaded into a Pandas DataFrame.
2. **Data Preparation**: The features are separated from the target variable (species).
3. **Train-Test Split**: The dataset is split into training and testing sets (80% training, 20% testing).
4. **Model Training**: A k-NN classifier with `k=3` is trained on the training data.
5. **Predictions**: The model makes predictions on the test set.
6. **Performance Evaluation**: The accuracy of the model is calculated, and a confusion matrix is generated to visualize the classification results.
7. **Cross-Validation**: A 5-fold cross-validation is performed to ensure model stability and robustness.

## Usage
To run this project, ensure you have Python and the required libraries installed. Execute the script that contains the implementation of the classification model, and it will load the Iris dataset, train the k-NN model, and display the performance metrics.

## Results
The results of the model will include the accuracy score and a confusion matrix that visualizes the performance of the classifier. You can adjust the parameters and explore different values of `k` to see how they affect model performance.

## Contributing
Contributions are welcome! If you have suggestions for improvements or find bugs, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
