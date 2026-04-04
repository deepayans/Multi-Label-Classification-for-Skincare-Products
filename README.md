# Multi-Label Classification for Skincare Products

## 📌 Overview

This project focuses on building a **multi-label classification model** to categorize skincare products based on their properties, ingredients, or intended use.

Unlike traditional classification tasks where each item belongs to a single class, this project allows a product to belong to **multiple categories simultaneously** (e.g., *moisturizing*, *anti-aging*, *acne-fighting*).

---

## 🚀 Features

* Multi-label classification pipeline
* Data preprocessing and cleaning
* Feature extraction (text-based or structured data)
* Model training and evaluation
* Performance metrics for multi-label tasks

---

## 🧠 Problem Statement

Skincare products often serve multiple purposes. The goal is to:

* Predict multiple labels per product
* Improve product categorization
* Enable better search and recommendation systems

---

## 🗂️ Project Structure

```
├── data/               # Dataset files
├── notebooks/          # Jupyter notebooks for exploration
├── src/                # Source code (models, preprocessing, utils)
├── models/             # Saved trained models
├── results/            # Outputs and evaluation results
└── README.md
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/deepayans/Multi-Label-Classification-for-Skincare-Products.git
cd Multi-Label-Classification-for-Skincare-Products
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 📊 Usage

Run training:

```bash
python train.py
```

Evaluate model:

```bash
python evaluate.py
```

---

## 📈 Evaluation Metrics

Common metrics for multi-label classification:

* Hamming Loss
* Precision, Recall, F1-score
* Subset Accuracy

---

## 🛠️ Technologies Used

* Python
* Scikit-learn
* Pandas & NumPy
* Matplotlib / Seaborn
* (Optional) Deep Learning frameworks like TensorFlow or PyTorch

---

## 🔍 Future Improvements

* Use transformer-based models (e.g., BERT)
* Hyperparameter tuning
* Deployment via API
* Real-time product classification

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 📬 Contact

For questions or collaboration, feel free to reach out via GitHub.

---
