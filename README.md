🧠Brain Tumor Segmentation & Classification using Deep Learning

A deep learning-based web application for detecting and classifying brain tumors from MRI scans using 3D-UNet for segmentation and CNN/VGG16 for classification.

Project Overview

Brain tumors are life-threatening and require early, accurate diagnosis for effective treatment. This project implements an end-to-end AI-based diagnostic system that:

🔹 Segments tumor regions from MRI scans using 3D-UNet

🔹 Classifies tumors into types using CNN and VGG16

🔹 Provides an interactive Django web interface for image upload, prediction, and visualization

🧠 Tumor Types Covered

✅ Glioma
✅ Meningioma
✅ Pituitary
✅ No Tumor

💡 Highlights

📁 Upload MRI scans via the web interface

⚙️ Preprocessing pipeline for image normalization and resizing

🧠 3D-UNet architecture for spatial tumor segmentation

🔬 CNN & VGG16 classifiers for tumor type prediction

📊 Evaluation using accuracy, precision, recall, F1-score, confusion matrix

🖼️ Result visualization with segmented tumor images and predicted class

🧪 Tech Stack

| Category      | Technology                      |
| ------------- | ------------------------------- |
| Language      | Python                          |
| Web Framework | Django                          |
| Deep Learning | TensorFlow / Keras              |
| Architectures | 3D-UNet, CNN, VGG16             |
| Dataset       | BraTS Dataset (Brain Tumor MRI) |

📂 Project Structure

brain-tumor-segmentation/
│
├── dataset/                  # MRI images (train/test)
├── segmentation/            # 3D-UNet model and training code
├── classification/          # CNN/VGG16 model and training
├── webapp/                  # Django app (views, templates, urls)
├── static/                  # CSS/JS assets
├── templates/               # HTML pages
├── media/                   # Uploaded images
├── manage.py                # Django entry point
├── requirements.txt         # Required Python packages
└── README.md                # Project documentation

🧠 Deep Learning Models Used

🔹 3D-UNet – Tumor Segmentation
Handles volumetric MRI data

Encoder-decoder with skip connections

Improved spatial accuracy for tumor boundaries

🔹 CNN & VGG16 – Tumor Classification

CNN for lightweight feature extraction

VGG16 (pre-trained) for higher classification accuracy

Output: glioma, meningioma, pituitary, or no tumor

🧩 Modules

Upload MRI Dataset

Preprocess and Split Data

Train 3D-UNet for segmentation

Train CNN/VGG16 for classification

Predict Tumor & Show Results


