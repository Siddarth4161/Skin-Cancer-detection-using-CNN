Automated Detection of Skin Cancer Using Deep Learning
A Comparative Analysis of CNN, Transfer Learning Models & Vision Transformers
 Overview

This project presents a complete deep-learning pipeline for automated skin cancer detection using dermatoscopic images from the HAM10000 dataset.
Multiple architectures—including CNN, VGG16, VGG19, InceptionV3, ResNet50, and Vision Transformer (ViT)—were trained and compared to identify the best-performing model.
The study evaluates each model’s ability to classify seven types of skin lesions, addressing critical challenges such as class imbalance, intra-/inter-class variability, and limited dataset size.

 Dataset

HAM10000 – Human Against Machine with 10,000 Training Images
Contains high-resolution dermatoscopic skin lesion images categorized into:

MEL — Melanoma

NV — Melanocytic Nevus

BKL — Benign Keratosis

BCC — Basal Cell Carcinoma

AKIEC — Actinic Keratoses

VASC — Vascular Lesion

DF — Dermatofibroma

Dataset preprocessing, metadata integration, oversampling, augmentation, and train/validation splitting followed the pipeline described in the report.
