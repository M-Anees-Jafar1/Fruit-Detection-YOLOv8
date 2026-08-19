# 🍎 Fruit Detection using YOLOv8

This repository contains training and inference pipelines for multi-class fruit detection using YOLOv8 in Google Colab.

---
## 📌 Key Features
* 📊 **Custom Dataset Training:** Trained YOLOv8 model for 50 epochs on annotated fruit datasets.
* 🖼️ **Flexible Inference:** Supports single image prediction, random batch evaluation (10 images), and full video stream detection.
* 🎥 **Video Codec Optimization:** Integrated `ffmpeg` (H.264 / `libx264` codec) pipeline to ensure smooth browser playback for rendered videos.
* 🚀 **Evaluation Metrics:** Evaluated model performance using mean Average Precision (`mAP50`).

## 📁 Dataset & Model Weights

Due to GitHub file size limits (>100MB), dataset zip files and trained weights are hosted on Google Drive:

* 📦 **Dataset (ZIP):** [Download Fruits Detection Dataset](https://drive.google.com/file/d/1DCwsZJ_bl4JAxj8ITi--gDmKJeG8G2dh/view?usp=sharing)
* 🧠 **Trained Model Weights (`fruit_best.pt`):** [Download Model Weights](https://drive.google.com/file/d/1GZydgD9Kk7dWW1DfkEN-pPpV2vdXjNC0/view?usp=sharing)

---

## 🚀 Notebooks Included
1. **Training Pipeline:** Model setup, YAML config, and training for 50 epochs.
2. **Inference Pipeline:** Single image prediction, batch prediction, and video processing with H.264 re-encoding.
## 🚀 Repository Structure

```text
├── Fruit_Detection_Training.ipynb   # Dataset extraction, YAML setup & 50-epoch training
├── Fruit_Detection_Inference.ipynb  # Validation, batch prediction & video detection
└── README.md                        # Project documentation
