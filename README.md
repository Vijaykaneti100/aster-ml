# AsterML - AI Smart Mirror Model

### 📌 Project Overview
This repository contains the machine learning model for "Aster", an AI-powered smart mirror. The model is designed to classify clothing attributes and recommend outfits, helping users reduce decision fatigue and make smarter purchasing choices.

### 🧠 Model Architecture
*   **Base Model:** MobileNetV3-small (pre-trained on ImageNet)
*   **Classifier:** Modified final layer for 10-class clothing attribute classification.
*   **Framework:** PyTorch

### 📊 Dataset
*   **Fashion-MNIST:** Used for initial training and testing. Contains 10 classes of clothing (T-shirt, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot).

### 🚀 How to Run
1. Open the `aster_classifier.ipynb` notebook in Google Colab.
2. Run the cells sequentially to install dependencies, load the dataset, and train the model.
3. The model weights will be saved as `aster_classifier.pth`.

### 📈 Results
*   Successfully trained for 1 epoch.
*   Model loss decreased from ~0.74 to ~0.16, indicating effective learning.

### 👨‍💻 Author
kaneti vijaya durga - AICTE Internship Project
