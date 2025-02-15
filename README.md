# Image Classification with PyTorch 🖼️🤖

This project demonstrates **image classification** using **PyTorch** on the **Tiny ImageNet dataset**. The goal is to classify images into 200 categories using a simple neural network. 🎯📊

---

## Table of Contents 📑
1. [Overview](#overview-)
2. [Installation](#installation-)
3. [Usage](#usage-)
4. [Code Structure](#code-structure-)
5. [Results](#results-)
6. [License](#license-)

---

## Overview 🚀

This project:
- Uses **PyTorch** to build and train a simple neural network for image classification. 🤖📸
- Leverages the **Tiny ImageNet dataset** for training and validation. 🧠🔍
- Implements data preprocessing, model training, and evaluation. 📊📉

---

## Installation 🛠️

To run this project, you need to install the required libraries. Run the following commands:

```bash
!pip install torch torchvision
```

---

## Usage 🖥️

1. **Load Dataset**: The script downloads and loads the Tiny ImageNet dataset.
2. **Preprocess Data**: Applies data augmentation and normalization.
3. **Build Model**: Defines and trains a simple neural network.
4. **Evaluate Model**: Evaluates the model's performance on the validation set.
5. **Save Model**: Saves the trained model for future use.

---

## Code Structure 🗂️

- **Data Preparation**:
  - Downloads and preprocesses the Tiny ImageNet dataset.
  - Applies data augmentation and normalization.

- **Model Definition**:
  - Defines a simple neural network with fully connected layers.
  - Uses cross-entropy loss for training.

- **Training**:
  - Trains the model using the training set.
  - Tracks training and validation loss.

- **Evaluation**:
  - Evaluates the model's performance on the validation set.
  - Prints the validation accuracy.

- **Model Saving**:
  - Saves the trained model for future use.

---

## Results 📊

- **Training/Validation Loss**: The model achieves low training and validation loss.
- **Validation Accuracy**: Evaluates the model's performance on the validation set.

---

## License 📜

This project is licensed under the **MIT License**. Feel free to use, modify, and distribute it as needed.

---

## Example Output 🖼️

Here’s an example of the model's training progress:

```plaintext
Epoch 1/20: Training Loss: 1.123, Validation Loss: 0.987, Accuracy: 0.45
Epoch 2/20: Training Loss: 0.987, Validation Loss: 0.876, Accuracy: 0.50
```

---

## Dependencies 📦

- `torch`
- `torchvision`

---

## Author 👨‍💻

This project was created by **[Navid Falah](https://github.com/navidfalah)**. Feel free to reach out for questions or collaborations at **navid.falah7@gmail.com**! 🤝
