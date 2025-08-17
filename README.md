# Deep Learning Classification Model (PyTorch)

This repository contains an end-to-end deep learning project built in **PyTorch** for binary classification on tabular data.  
The project demonstrates the complete workflow of preparing data, building and training a neural network, evaluating performance, and performing inference on new inputs.  

---

## Project Overview
- **Data Preparation**: Loaded tabular dataset, applied normalization, and split into training, validation, and test sets.  
- **Model Architecture**: Implemented a custom feedforward neural network using `torch.nn.Module`.  
- **Training**: Trained the model using the **Adam optimizer** and **Binary Cross-Entropy Loss (BCELoss)** with a validation loop to track performance.  
- **Evaluation**: Tested the model on unseen data to assess accuracy and reliability.  
- **Inference**: Included functionality to preprocess new inputs and generate predictions with the trained model.  

---

## Tech Stack
- **Python 3**  
- **PyTorch**  
- **NumPy / Pandas**  
- **Matplotlib / Seaborn** (for visualizations)  

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/deep-learning-classification.git
   cd deep-learning-classification
