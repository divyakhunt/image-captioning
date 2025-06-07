# 🖼️ Image Captioning using Deep Learning (CNN + LSTM)

This project generates natural language captions for images using a combination of convolutional neural networks (CNNs) and recurrent neural networks (RNNs). It uses DenseNet201 for image feature extraction and LSTM for sequence generation.

---

## 📂 Dataset

- **Flickr8k Dataset** from Kaggle: [Link](https://www.kaggle.com/datasets/adityajn105/flickr8k)
- Contains 8000 images with 5 captions each.

---

## 🧠 Model Architecture

- **CNN Encoder**: DenseNet201 (pretrained on ImageNet)
- **RNN Decoder**: LSTM layers with embedding and dense layers
- Custom data generator class (`CustomDataGenerator`) for training

---

## 🔧 Features

- Text preprocessing and cleaning
- Custom tokenizer and padding for caption sequences
- Feature extraction using DenseNet201
- Training and validation split (85%-15%)
- Caption generation with greedy search

---

## 📁 File Structure

- `image_captioning.ipynb`: Main Jupyter notebook
- `features.pkl`: Extracted image features (binary format)
- `tokenizer.pkl`: Trained tokenizer (binary format)
- `model.keras`: Trained model file (if included)
- `captions.txt`: Raw caption data

---

## 💻 How to Run

1. Install required packages:
   ```bash
   pip install -r requirements.txt

