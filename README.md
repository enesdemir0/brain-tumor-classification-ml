# Brain Tumor Classification with HOG + Random Forest

This project uses **classic machine learning techniques** to classify brain tumor MRI images as either `"tumor"` or `"no tumor"`. Instead of using deep learning, we apply handcrafted **Histogram of Oriented Gradients (HOG)** features and a **Random Forest** classifier. The goal is to demonstrate traditional ML approaches to image classification in a clean and interpretable way.

---

## Features

- Uses MRI images resized to 64×64 grayscale
- HOG feature extraction to encode texture and shape
- Random Forest classifier trained on HOG features
- Evaluation using precision, recall, F1-score, and accuracy
- Visualizations: HOG feature images, precision-recall vs. threshold plot

---

## Project Structure
brain-tumor-classification-ml/
│
├── brain_tumor_dataset/
│ ├── yes/ # Tumor images
│ └── no/ # Non-tumor images
│
├── Brain_Tumor_Classification_HOG_RF.ipynb # Main notebook
├── README.md


## Dataset

- **Source:** [Brain MRI Images for Brain Tumor Detection – Kaggle](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)
- **Total Samples:** 253 images
- **Classes:** `yes` (tumor) and `no` (no tumor)

##  Requirements

```bash
pip install scikit-learn matplotlib pillow numpy scikit-image seaborn


##  Final Model Performance (Threshold = 0.64)

| Metric       | Score |
|--------------|-------|
| Accuracy     | 0.92  |
| Precision    | 0.94  |
| Recall       | 0.94  |
| F1-score     | 0.94  |




