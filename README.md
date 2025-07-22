# NLP-Image-Caption-Generator
# Image Caption Generator using Deep Learning | NLP Project

This project implements a deep learning-based image caption generator that combines computer vision and natural language processing (NLP) techniques. The model is trained on the Flickr8k dataset, where it learns to generate meaningful and contextually accurate captions for input images.
## ✨ Key Features
- Preprocessing and feature extraction using pretrained CNN (InceptionV3 or VGG16).
- Text preprocessing with tokenizer and vocabulary mapping.
- Sequence generation using LSTM-based language model.
- Beam search and greedy decoding strategies for caption prediction.
- Evaluation using BLEU score.
## 📦 Dataset
- **Flickr8k Dataset**: Contains 8,000 images with five captions each.  
  Download link: [Flickr8k]
## 📂 Project Structure
- `Git NLP Project.ipynb` – Main Jupyter notebook with model pipeline, training and inference.
- `images/` – Sample input images and output captions.
- `models/` – Saved model weights and tokenizer.
## 🚀 How to Run
1. Install dependencies from `requirements.txt`.
2. Download and extract the Flickr8k dataset.
3. Run the notebook to train the model or generate captions.
## 🔍 Future Work
- Integrate attention mechanisms.
- Switch to Transformer-based captioning (e.g., using ViT + GPT-2).
- Extend to multilingual caption generation.
## 👨‍💻 Author
Pavan B | Final Year B.Tech CSE-AI Student | Amrita University
