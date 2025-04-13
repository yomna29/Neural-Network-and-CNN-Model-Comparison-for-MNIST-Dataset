Neural Network and CNN Model Comparison for MNIST Dataset
This project explores the performance of neural networks (NN) and convolutional neural networks (CNN) on the MNIST dataset. The notebook implements a systematic comparison of models with varying configurations, including the number of layers, number of nodes, learning rates, batch sizes, and the use of dropout regularization.
## Features
•	Data Preprocessing: MNIST dataset is split into training, validation, and test sets, with normalization and reshaping applied.

•	Model Creation: Flexible model generation with configurable parameters such as:

    o Number of layers

    o Number of nodes per layer

    o Dropout probability

    o Learning rate

    o Batch size

•	Training and Evaluation: Models are trained and evaluated with and without dropout to assess the impact of regularization.

• Visualization:

     o Training and validation accuracy/loss plots for all configurations.

     o Confusion matrices for the best-performing models.

•	Best Model Selection: Automatically identifies the best-performing model 
based on validation accuracy and evaluates it on the test set.

## Results
    • Comparison of NN and CNN models across various configurations.
    • Identification of the best-performing model with detailed metrics, including test accuracy, loss, and classification report.
## Requirements
    • Python 3.x
    • TensorFlow, Keras, PyTorch, NumPy, Matplotlib, scikit-learn
Usage
Run the notebook to:
1.	Train and evaluate models with different configurations.
2.	Visualize training results and confusion matrices.
3.	Identify and test the best-performing model.

