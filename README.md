# EuroSAT Land Cover Classification

A deep learning project for land cover image classification using the EuroSAT satellite image dataset.

This project explores multiple Convolutional Neural Network (CNN) architectures and training strategies for classifying satellite images into 10 land cover categories.

---

## 📋 Project Overview

The main goal of this project is to investigate how architectural choices and regularization techniques affect image classification performance on remote sensing data.

Experiments include:

- Logistic Regression baseline
- Custom CNN models
- Deeper CNN architectures
- Data augmentation
- Dropout regularization
- Increased training epochs
- Early stopping

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn
- Seaborn
- Jupyter Notebook

---

## 📂 Repository Structure

```text
EuroSAT-Land-Cover-Classification/
│
├── notebooks/
│   └── EuroSAT .ipynb
│
├── requirements.txt
└── README.md
```

---

## 📊 Dataset

Dataset used:

- EuroSAT RGB dataset
- 10 land cover classes
- Satellite imagery for remote sensing classification

Classes include:

- AnnualCrop
- Forest
- HerbaceousVegetation
- Highway
- Industrial
- Pasture
- PermanentCrop
- Residential
- River
- SeaLake

---

## 🧪 Experiments and Results

| Model / Experiment | Test Accuracy |
|---|---|
| Logistic Regression Baseline | 39.5% |
| Baseline CNN | 81.9% |
| Augmented Deep CNN | 86.9% |
| Dropout CNN | 84.1% |
| Dropout + 20 Epochs | 89.9% |
| EarlyStopping CNN | **90.5%** |

---

## 📈 Key Findings

- CNNs significantly outperform classical machine learning baselines.
- Data augmentation improves generalization performance.
- Dropout helps reduce overfitting.
- Increasing epochs alone does not always improve results.
- Combining augmentation, dropout, and early stopping produced the best performance.

---

## 📓 Notebook

Main notebook:

- [`EuroSAT .ipynb`](notebooks/EuroSAT%20.ipynb)

The notebook includes:

- Data loading and preprocessing
- EDA and visualization
- Model implementation
- Training and evaluation
- Learning curves
- Confusion matrix analysis
- Experiment comparison

---

## 🚀 Future Improvements

- Transfer learning with pretrained CNNs
- ResNet / EfficientNet experiments
- Hyperparameter tuning
- Model deployment with Streamlit or Gradio
- Additional remote sensing datasets

---

## 👤 Author

Ali Alavi
