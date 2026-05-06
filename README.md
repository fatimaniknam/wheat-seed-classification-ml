# 🌾 Wheat Seed Classification using Machine Learning

## 📌 Project Overview

This project applies machine learning techniques to classify different wheat seed varieties based on morphological characteristics of wheat kernels.

The objective of this study was to investigate whether measurable kernel traits such as size, shape, and structural properties can accurately distinguish between wheat varieties.

A Random Forest classifier was trained using real agricultural data, and the model achieved approximately **88% classification accuracy**.

---

## 🌱 Motivation

Accurate classification of wheat varieties is important in agricultural science, crop quality assessment, and seed selection.

Traditional manual classification methods can be time-consuming and subjective. Machine learning offers an efficient and scalable approach for identifying wheat varieties based on measurable morphological features.

This project demonstrates how data-driven methods can support agricultural research and crop analysis.

---

## 📊 Dataset Description

The dataset contains quantitative measurements extracted from wheat kernel images using soft X-ray imaging techniques.

Each row represents one wheat kernel sample.

### Features Used

| Feature | Description |
| A | Area of kernel |
| P | Perimeter of kernel |
| C | Compactness |
| LK | Kernel Length |
| WK | Kernel Width |
| A_Coef | Asymmetry Coefficient |
| LKG | Length of Kernel Groove |

### Target Variable

The target column represents three wheat varieties:

- 0 → Wheat Variety 1
- 1 → Wheat Variety 2
- 2 → Wheat Variety 3

---

## 🤖 Machine Learning Model

A **Random Forest Classifier** from Scikit-learn was used for classification.

### Workflow

1. Data loading and preprocessing
2. Train-test split
3. Model training using Random Forest
4. Prediction and evaluation
5. Feature importance analysis

---

## 📈 Results

The model achieved approximately:

- ✅ **Accuracy: 88%**

The classification report and confusion matrix indicated strong overall performance.

Class 1 achieved nearly perfect classification, while some confusion occurred between class 0 and class 2, suggesting morphological similarity between these wheat varieties.

---

## 📊 Confusion Matrix

![Confusion Matrix](confusion_matrix.png)

---

## 🔍 Feature Importance Analysis

Feature importance analysis showed that kernel size and structural characteristics were the most influential factors in distinguishing wheat varieties.

Among all measured traits, the following features contributed the most to classification performance:

- Area (A)
- Length of Kernel Groove (LKG)
- Perimeter (P)

These findings suggest that overall kernel morphology plays a major role in varietal differentiation.

In contrast, compactness and asymmetry coefficient contributed less to classification, indicating that these traits may be more conserved across the studied wheat varieties.

The observed importance of size-related features may reflect underlying phenotypic and potentially genetic differences among wheat cultivars.

This analysis demonstrates how machine learning models can provide not only predictive performance, but also biologically meaningful insights into agricultural datasets.

![Feature Importance](feature_importance.png)

---

## 🧠 Biological Interpretation

The results indicate that morphological traits contain sufficient discriminatory information for wheat variety classification.

The overlap observed between some classes may reflect similarities in kernel morphology and potentially shared biological characteristics.

This project highlights the usefulness of machine learning methods in agricultural and biological data analysis.

---

## 🛠 Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

## 🚀 Future Improvements

Possible future developments include:

- Applying advanced models such as XGBoost or Support Vector Machines
- Performing hyperparameter tuning
- Using larger agricultural datasets
- Integrating genomic data such as SNP markers
- Exploring deep learning approaches

---

## 📂 Project Structure

```text
wheat-seed-classification-ml/
│
├── Seed_Data.csv
├── wheat_model.ipynb
├── confusion_matrix.png
├── feature_importance.png
└── README.md

---
Author

Fatemeh Niknam  
MSc in Agronomy & Plant Breeding  
Toronto, Canada

---
Notes

This project is part of a practical machine learning application in agriculture and demonstrates real-world data analysis.
