 Wheat Seed Classification using Machine Learning

Project Overview
This project aims to classify different wheat varieties using machine learning techniques based on morphological features of wheat kernels.

The model learns patterns from physical characteristics such as size, shape, and structure to accurately distinguish between different classes of wheat.

 Dataset Description
The dataset contains measurements of wheat kernels collected using soft X-ray imaging techniques.

Features:
- A  Area
- P  Perimeter
- C  Compactness
- LK  Kernel Length
- WK  Kernel Width
- A_Coef  Asymmetry Coefficient
- LKG  Kernel Groove Length

Target:
- 0 ? Wheat Type 1  
- 1 ? Wheat Type 2  
- 2 ? Wheat Type 3  

---

Model Used
A **Random Forest Classifier** was used to train the model and predict wheat classes.

---

Results

- Accuracy: **88%**
- Strong performance in classifying wheat varieties
- Perfect classification observed in one class (Class 1)

---

Key Insights

- The most important features were:
  - Area (A)
  - Kernel Groove Length (LKG)
  - Perimeter (P)

- Misclassification mainly occurred between Class 0 and Class 2 indicating similarity in their morphological characteristics

---

Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

How to Run

1. Upload dataset (`Seed_Data.csv` (downloaded from Kaggle.com) to Google Colab)
2. Run the notebook step by step
3. Train the model and evaluate performance

---

Conclusion

This project demonstrates that morphological features are highly effective in distinguishing wheat varieties.

Machine learning models can support agricultural research by providing accurate and fast classification.

---

 Future Work

- Apply advanced models (XGBoost, SVM, Neural Networks)
- Use larger datasets
- Integrate genetic (genomic) data for higher accuracy

---
Author

Fatemeh Niknam  
MSc in Agronomy & Plant Breeding  
Toronto, Canada

---
Notes

This project is part of a practical machine learning application in agriculture and demonstrates real-world data analysis.
