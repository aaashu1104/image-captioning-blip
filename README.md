# 🧠 Image Captioning with Visual Attention

This project generates natural language captions for images using an encoder-decoder architecture with Bahdanau Attention — inspired by the paper *"Show, Attend and Tell"*.

## 📸 Example Output
**Input Image:** (Upload an image in Colab)  
**Generated Caption:** “A group of people standing in a kitchen preparing food.”

---

## 🚀 Key Features
- 🎯 **Encoder**: InceptionResNetV2 for extracting image features
- ✍️ **Decoder**: GRU-based with attention mechanism
- 📁 **Dataset**: MS-COCO 2014 captions dataset
- 🎓 Trained on Google Colab (GPU accelerated)
- 📤 Custom image upload and caption generation

---

## 🛠️ How to Run

1. **Open in Colab**  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1Ndxq_xWgtY-ztiKAmeRLw4-WX2S6fg3x?usp=sharing)

2. **Upload your own image** in the Colab interface

3. **Generate Captions** with the trained model

---

## 🧱 Model Architecture

```text
Encoder (InceptionResNetV2)
    ↓
Feature Vector (64x2048)
    ↓
Bahdanau Attention
    ↓
GRU Decoder
    ↓
Caption Output
