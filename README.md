# 🏷️ KNN Classifier - IRIS Dataset

## 🚀 Project Overview

This project implements a **K-Nearest Neighbors (KNN)** classifier using Python and Scikit-learn. It focuses on the **Iris dataset** and demonstrates the full workflow of training, evaluating, and visualizing KNN models.

Key features include:

* Data preprocessing
* Model training with varying K values
* Accuracy evaluation
* Confusion matrix visualization
* Decision boundary visualization

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
* **Evaluation:** Uses accuracy metrics and confusion matrices.
* **Visualization:** Decision boundaries plotted for better understanding of model performance.

---

## ⚡ Usage

1. Prepare the data using `data-preprocessing.py`.
2. Open and run `knn-classify.ipynb` to train and evaluate KNN models.
3. Check saved plots and models in their respective folders.

---

## 🤝 Contributions

Contributions are welcome! Feel free to open a pull request or report issues.

---

## 📜 License

This project is licensed under the MIT License.

---

## 😊 Author

**Gautham DV**
