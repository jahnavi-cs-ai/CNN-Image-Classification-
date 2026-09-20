# CNN Image Classification using TensorFlow & Keras

A multi-class image classification project built using a **Convolutional Neural Network (CNN)** with **TensorFlow** and **Keras**.

The model is trained on the **CIFAR-10 dataset** to classify images into 10 different categories.

---

## Project Overview

This project demonstrates the implementation of a CNN for image classification.

The model learns important visual features from images using convolutional and pooling layers and predicts the corresponding class using a Softmax output layer.

The CIFAR-10 dataset contains 10 image classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

---

## Project Workflow

1. Load the CIFAR-10 dataset
2. Normalize image pixel values
3. Build a Convolutional Neural Network
4. Train the model using training data
5. Use validation data to monitor model performance
6. Evaluate the trained model on the test dataset
7. Visualize training and validation accuracy

---

## CNN Architecture

The model contains:

- Convolutional Layer
- Max Pooling Layer
- Convolutional Layer
- Max Pooling Layer
- Flatten Layer
- Dense Layer
- Dropout Layer
- Softmax Output Layer

Dropout is used to reduce overfitting and improve generalization.

---

## Installation

Clone this repository:

```bash
git clone <your-repository-url>
```

Move into the project directory:

```bash
cd CNN-Image-Classification
```

Install the required libraries:

```bash
pip install tensorflow numpy matplotlib jupyter
```

---

## Run the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
CNN_Image_Classification.ipynb
```

Run all cells in sequence.

---

## Model Training

The model is trained using the Adam optimizer with Sparse Categorical Crossentropy as the loss function.

```python
model.compile(
    optimizer="adam",
    loss="sparse_categorical_crossentropy",
    metrics=["accuracy"]
)
```

Training and validation accuracy are monitored during training.

---

## Results

After training, the model is evaluated on the CIFAR-10 test dataset.

The notebook displays:

- Test Accuracy
- Training Accuracy
- Validation Accuracy
- Accuracy vs Epoch graph

Actual performance may vary depending on training configuration, TensorFlow version, and hardware.

---

## Project Structure

```text
CNN-Image-Classification/
│
├── CNN_Image_Classification.ipynb
└── README.md
```

---

## Future Improvements

Possible improvements include:

- Data augmentation
- Batch normalization
- Hyperparameter tuning
- Confusion matrix visualization
- Precision, recall, and F1-score evaluation
- Custom image prediction
- Transfer learning using models such as MobileNet or ResNet

---

## Key Learnings

Through this project, I worked with:

- Convolutional Neural Networks
- Image preprocessing
- Multi-class classification
- TensorFlow and Keras
- Model training and validation
- Overfitting control using Dropout
- Performance visualization

---

## Author

**Jahnavi Nekkanti**

B.Tech Student | Python | Data Science | Machine Learning | AI