# PyTorch Training Pipeline for Binary Classification

## 📌 Project Description
This project implements a complete neural network training pipeline using PyTorch for a binary classification task (Cyberbullying detection type dataset).

The implementation demonstrates a full machine learning workflow, including:
- Forward propagation
- Loss computation
- Backpropagation
- Optimizer-based parameter updates
- Gradient resetting
- Model evaluation on test data

---

## 🧠 Model Architecture

The neural network is a simple feedforward model:

Input Layer: 4 features  
Hidden Layer: 8 / 16 neurons (ReLU activation)  
Output Layer: 1 neuron (Sigmoid activation)

---

## ⚙️ Training Process

The model is trained using the following steps:

1. Forward Pass → Generate predictions from input data  
2. Loss Computation → Calculate error between prediction and actual label  
3. Backward Pass → Compute gradients using backpropagation  
4. Optimizer Step → Update model weights  
5. Zero Gradients → Reset gradients to prevent accumulation  

The model is trained for **100 epochs**.

Loss is printed every 10 epochs and stored for analysis.

---

## 📊 Training Results

### Training Loss (Example Output)

Epoch: 0 Loss: 0.3381  
Epoch: 10 Loss: 0.3170  
Epoch: 20 Loss: 0.2967  
Epoch: 30 Loss: 0.2773  
Epoch: 40 Loss: 0.2589  
Epoch: 50 Loss: 0.2416  
Epoch: 60 Loss: 0.2254  
Epoch: 70 Loss: 0.2103  
Epoch: 80 Loss: 0.1962  
Epoch: 90 Loss: 0.1831  

---

## 📈 Evaluation Results

- Train Accuracy: 1.0  
- Test Accuracy: 1.0  

The model shows perfect performance on both training and test datasets.

---

## 🔁 Model Modification Experiment

A modified version of the model was tested by increasing the number of hidden neurons:

- Original: 8 neurons  
- Modified: 16 neurons  

### Observations:
- Loss decreased more slowly in the modified model
- Convergence became more gradual
- No significant improvement in accuracy

---

## 📊 Comparison Summary

| Model Version | Hidden Neurons | Performance | Convergence |
|--------------|----------------|-------------|-------------|
| Original     | 8              | High        | Faster      |
| Modified     | 16             | Similar     | Slower      |

---

## 🧪 Conclusion

- The training pipeline successfully learns patterns from the dataset.
- The model achieves perfect accuracy on both train and test sets.
- Increasing model complexity does not always improve performance.

---

## 🛠️ Technologies Used

- Python  
- PyTorch  
- NumPy  
- Scikit-learn  

---
