# Handwritten Text Generation using Autoencoder

## 📌 Project Overview
This project focuses on generating handwritten text using an **Autoencoder** model trained on the **IAM Handwriting Dataset**. The goal is to learn a compressed representation of handwritten text and reconstruct it using deep learning techniques.

## 📂 Dataset
The **IAM Handwriting Dataset** consists of handwritten English text images. It is widely used for handwriting recognition and generation tasks.

## 🚀 Features
- **Preprocessing of Handwritten Text:** Converts images to grayscale, resizes them, and normalizes pixel values.
- **Autoencoder-Based Model:** Uses convolutional layers to encode and decode handwritten text images.
- **Image Reconstruction:** Compares original and reconstructed handwritten images.
- **Customizable Model Architecture:** Allows modifications to encoder and decoder layers.
- **Training and Evaluation Pipeline:** Supports training from scratch with hyperparameter tuning.
- **Scalability:** Can be extended to larger datasets and more complex architectures.
- **Future Enhancements:** Planned improvements include **GAN-based** text generation and **Variational Autoencoders (VAE)**.

## 🔧 Installation
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/shashikant-kamble/Handwritten-Text-Generation.git
cd Handwritten-Text-Generation
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Download Dataset
- Download the **IAM Handwriting Dataset** from Kaggle.
- Extract the dataset inside the `dataset` folder.

## 🚀 Usage
### Train the Model
```bash
python train.py
```

### Evaluate the Model
```bash
python evaluate.py
```

## 🔮 Future Enhancements
- Extend the project to **GANs** for better text generation.
- Improve reconstruction quality using **Variational Autoencoders (VAE)**.
- Train on a larger handwriting dataset for better generalization.

## 👨‍💻 Author
**Shashikant Kamble**

