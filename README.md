# 🏷️ KNN Classifier - IRIS Dataset

## 🚀 Project Overview

This project implements a **K-Nearest Neighbors (KNN)** classifier using Python and Scikit-learn. It focuses on the **Iris dataset** and demonstrates the full workflow of training, evaluating, and visualizing KNN models.

Key features include:

* Data preprocessing
* Model training with varying K values
* Accuracy evaluation
* Confusion matrix visualization
* Decision boundary visualization
* **Cross-validation** analysis including normal and weighted KNN models
* Comparison of results to identify the best-performing model

---

## 🛠️ Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/gauthamdv/knn-classifier.git
cd knn-classifier
```

### 2️⃣ Install requirements

```bash
pip install -r requirements.txt
```

### 3️⃣ Prepare the Data

Run the preprocessing script to clean and prepare the dataset stored in the `datasets/` folder:

```bash
python data-preprocessing.py
```

### 4️⃣ Run the Notebook

Open `knn-classify.ipynb` to:

* Train KNN models with different K values

* Evaluate performance using accuracy and confusion matrices

* Visualize decision boundaries

* Perform **cross-validation** analysis (normal and weighted)

* Compare results

* Identify the best-performing model based on the analysis (in this case, the regular weighted KNN model)

* **Data:** `datasets/`

* **Models saved in:** `models/`

* **Plots saved in:** `plots/`

---

## 📁 File Structure

```text
knn-classifier/
├── datasets/                  # Raw and processed datasets
├── models/                    # Saved models
├── plots/                     # Visualizations and plots
├── .gitignore                 # Git ignore file
├── README.md                  # Project documentation (this file)
├── data-preprocessing.py      # Data preprocessing script
├── knn-classify.ipynb         # Jupyter notebook for KNN classification
└── requirements.txt           # Python dependencies
```

---

## 📊 Models & Evaluation

* **KNN Classifier:** Trained with multiple K values to find the optimal K.
* **Cross-Validation:** Evaluates normal and weighted KNN models and compares performance.
* **Best Model Selection:** After analyzing the comparison, the regular weighted KNN model was chosen as the best-performing model.
* **Evaluation Metrics:** Uses accuracy and confusion matrices.
* **Visualization:** Decision boundaries plotted for better understanding of model performance.

---

## ⚡ Usage

1. Prepare the data using `data-preprocessing.py`.
2. Open and run `knn-classify.ipynb` to train, evaluate, and cross-validate KNN models.
3. Compare results and select the best-performing model.
4. Check saved plots and models in their respective folders.

---

## 🤝 Contributions

Contributions are welcome! Feel free to open a pull request or report issues.

---
