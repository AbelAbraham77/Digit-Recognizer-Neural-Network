# Digit Recognizer Neural Network

This project implements a simple neural network with two layers to recognize handwritten digits. The model achieves up to **86% accuracy** in predicting digits from the MNIST dataset.

---

## Project Overview
The digit recognizer is a two-layer feedforward neural network trained to classify handwritten digits (0-9). The model is designed for simplicity and efficiency, making it suitable for beginners exploring neural networks and digit classification.

### Key Features
- **Two-layer architecture**: A lightweight neural network structure.
- **High accuracy**: Achieves up to 86% accuracy.
- **MNIST dataset**: Uses the MNIST dataset, a standard benchmark for digit recognition tasks.
- **Code simplicity**: Focused on clear and modular implementation.

---

## Project Structure
```
├── src.ipynb           # Jupyter Notebook containing the code implementation.
├── README.md           # Project documentation.
```

---

## Requirements
To run this project, ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Required libraries:
  - TensorFlow/Keras
  - NumPy
  - Matplotlib


---

## Dataset
This project uses the **MNIST dataset** for handwritten digit classification. The dataset includes:
- **60,000 training images**
- **10,000 test images**

---

## Model Architecture
The model consists of two layers:
1. **Hidden Layer**: Fully connected layer with ReLU activation.
2. **Output Layer**: Fully connected layer with Softmax activation.

### Summary of the Model
| Layer             | Type            | Activation | Output Shape |
|-------------------|-----------------|------------|--------------|
| Input             | Flatten         | -          | (None, 784)  |
| Dense_1 (Hidden)  | Fully Connected | ReLU       | (None, 128)  |
| Dense_2 (Output)  | Fully Connected | Softmax    | (None, 10)   |

---

## Results
- **Training accuracy**: ~86%
- **Test accuracy**: ~85-86%

The accuracy can vary slightly depending on the initialization and the hyperparameters.

---

## How to Run the Project
1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook src.ipynb
   ```
3. Follow the instructions in the notebook to:
   - Load the dataset
   - Build the model
   - Train and evaluate the model

---

## Future Improvements
- Experiment with more hidden layers.
- Use advanced optimizers.
- Implement regularization techniques to improve generalization.

---

## License
This project is open-source and available under the MIT License.

---
