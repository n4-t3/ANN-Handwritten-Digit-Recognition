# Handwritten Digit Recognition with ANN

This project implements a simple Artificial Neural Network (ANN) from scratch to recognize handwritten digits from the MNIST dataset. The dataset is provided in CSV format, and the model is trained and evaluated for digit classification.

## Dataset

The dataset used in this project is the **MNIST** dataset, which contains 28x28 grayscale images of handwritten digits (0-9). You can find the dataset in CSV format [GTDLBench](https://git-disl.github.io/GTDLBench/datasets/mnist_datasets/).

### Instructions for Using the Dataset:
1. Download the MNIST dataset in CSV format from the link above.
2. Place the downloaded CSV files in the `data/` folder within the project directory (the CSV files should be named `mnist_train.csv` and `mnist_test.csv`).

## Project Overview

This project includes:
- **Data Preprocessing**: Loading and normalizing the MNIST CSV data.
- **ANN Architecture**: A simple feedforward neural network built from scratch using numpy (no external deep learning libraries).
- **Training**: Training the neural network using backpropagation and gradient descent.
- **Evaluation**: Evaluating the model on test data and calculating accuracy.

## Model

The ANN model consists of:
- An input layer with 784 neurons (corresponding to the 28x28 pixel image).
- A hidden layer with a configurable number of neurons (default set to 128).
- An output layer with 10 neurons (one for each digit).

## Model Testing Results

After training the model, it was evaluated using the test dataset. The resulting prediction is shown in the image below:

![Model Prediction Result](prediction.png)

**Note:** The results of the model are not entirely reliable as the model's performance can be improved significantly. Possible ways to improve the model include:
- **Increasing the number of neurons in the hidden layer** to improve learning capacity.
- **Using a more advanced optimization algorithm** like Adam instead of basic gradient descent.
- **Implementing regularization techniques** (e.g., dropout) to prevent overfitting.
- **Expanding the dataset** with more samples to improve generalization.

## License

This project is licensed under the BEER-WARE License - see the [LICENSE](LICENSE) file for details.
