# 🧠 Breast Cancer Diagnosis Classifier using KNN

Tugas ini merupakan implementasi **KNN Klassifier** model untuk mengklasifikasi apakah breast tumor dikategorikan sebagai **malignant (M)** or **benign (B)** menggunakan the Breast Cancer dataset.

## 📁 Dataset

Dataset diambil dari **`ucimlrepo.fetch_ucirepo.breast_cancer_wisconsin_diagnostic()`**, yang memiliki **30 features**.

- **Target**: 
  - `M` = Malignant (Ganas)
  - `B` = Benign (Jinak)
- **Total Instances**: 569
- **Features**: Radius, texture, perimeter, area, smoothness, etc.

## 🚀 Technologies

- Python 🐍
- Scikit-learn
- Jupyter Notebook or any Python IDE

## 🧪 Model Training

The dataset is split into:
- **80% training data**
- **20% testing data**

## 📊 Evaluation Results
- Dengan n_neighbors=5 didapatkan bahwa, F1-Score yang mengkalisifikasikan B (tumor jinak) lebih baik dari M (tumor ganas) yang mana F1-Score ini merupakan kombinasi dari precision dan recall dari masing-masing kelas.


