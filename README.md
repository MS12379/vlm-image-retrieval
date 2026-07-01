# vlm-image-retrieval
Vision-based image retrieval system using SigLIP embeddings and cosine similarity search
# Image Retrieval using SigLIP (VLM)

This project implements a simple image retrieval system using Vision-Language Models (SigLIP).

## 🔥 Features
- Image embedding using SigLIP model
- Cosine similarity for image search
- Top-K similar image retrieval

## 🧠 Pipeline
Image → Processor → SigLIP Model → Embedding → Cosine Similarity → Top-K Results

## 📦 Requirements
- torch
- transformers
- torchvision
- pillow

## 🚀 How to Run
1. Load images dataset
2. Generate embeddings
3. Run similarity search

## 📌 Output
Given a query image, the system returns the most similar images from the dataset.

## 🧪 Model
- google/siglip-base-patch16-224

---
Simple VLM image retrieval project.
