# Image Preprocessing Techniques
### Using Mini-ImageNet Dataset

## 📌 Overview
Implementation of five fundamental image
preprocessing techniques applied to the
Mini-ImageNet dataset. Includes visual
comparisons and structured analysis of
each transformation's impact on image data.

## 🧰 Techniques Implemented
| # | Technique | Purpose |
|---|-----------|---------|
| 1 | Resizing (64×64) | Uniform input for models |
| 2 | Normalization (0–1) | Stable, faster training |
| 3 | Grayscale Conversion | Reduce complexity |
| 4 | Horizontal Flipping | Data augmentation |
| 5 | Random Rotation (±20°) | Rotation invariance |

## 📂 Dataset
Mini-ImageNet — downloaded via KaggleHub
Industry-standard benchmark dataset for
image classification tasks.

## 🛠️ Libraries Used
- Python 3.x
- TensorFlow
- OpenCV
- NumPy
- Matplotlib
- KaggleHub

## ▶️ How to Run
pip install tensorflow matplotlib numpy
         opencv-python kagglehub

Run IDL_asg_2.ipynb in:
Jupyter Notebook or Google Colab

## 🔗 Connection to Deep Learning
These preprocessing techniques form the
foundation of any deep learning pipeline.
In my FYP (CardioSense), similar steps —
normalization, segmentation, and feature
extraction — were applied to PCG audio
signals before CNN-LSTM model training.

## 👨‍💻 Author
Hafiz Muhammad Haris
BS Computer Science
University of Central Punjab, Lahore
