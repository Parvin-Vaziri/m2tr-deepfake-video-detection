# Deepfake Video Detection (M2TR)

This project detects fake videos using deep learning.
It is based on an M2TR-style architecture and uses visual information only.

## What I did
- Sampled **10 frames** from each video
- Resized frames to **224 × 224**
- Used **RGB frames** and **FFT-based features**
- Applied a dual-stream model with transformers
- Trained and evaluated the model using PyTorch

## Dataset
The project uses the **Celeb-DF v2** dataset.
Due to license restrictions, the dataset is **not included** in this repository.

## Tools
- Python
- PyTorch
- OpenCV
- NumPy
