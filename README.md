# FaceID App – Facial Verification with Siamese Network

This is a facial verification system using a **Siamese Neural Network**. The model determines if two facial images belong to the same person — useful for tasks like auto-tagging people in photos, secure login, or event photo filtering.

## 🚀 How It Works

1. **Capture or upload a selfie**
2. **Compare** with a folder of verification images
3. **Siamese model** predicts similarity scores
4. **If enough matches** are above a threshold → Verified ✅

## 🧠 Model

A **Siamese neural network** is trained to generate similar embeddings for images of the same person and different embeddings for others. The final model is saved as `siamesemodel.h5`.
