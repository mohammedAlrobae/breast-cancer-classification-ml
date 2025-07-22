
# Breast Cancer Classification using Machine Learning

This project focuses on predicting breast cancer types (malignant or benign) using three different machine learning algorithms. The objective is to compare model performance and select the best algorithm for breast cancer classification.

## 📊 Project Description

Breast cancer is one of the most common cancers affecting women worldwide. Early detection and accurate classification of tumors are crucial for effective treatment. This notebook explores and compares three machine learning models on a labeled dataset of tumor characteristics.

## 🧠 Algorithms Used

- Logistic Regression
- Decision Tree Classifier
- Support Vector Machine (SVM)

## 📁 Dataset

The dataset used is the well-known **Breast Cancer Wisconsin Diagnostic Dataset**, which includes features like:
- Mean radius
- Texture
- Perimeter
- Area
- Smoothness
- ...and more

Target classes:
- `M` = Malignant
- `B` = Benign

## 📈 Evaluation Metrics

The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score

Example results:
```json
{
  "accuracy": 0.98,
  "recall": [0.98, 0.98],
  "precision": [0.99, 0.96],
  "f1_score": [0.98, 0.97]
}
```

## ✅ Conclusion

All three algorithms performed well, with high accuracy and recall. This shows machine learning's potential in aiding medical diagnosis. Logistic Regression and SVM had slightly better overall performance.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/mohammedAlrobae/breast-cancer-classification-ml.git
   ```
2. Open the notebook in Jupyter:
   ```bash
   jupyter notebook
   ```
3. Run all cells in order.

## 🛠️ Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install them using:

```bash
pip install -r requirements.txt
```

## 📬 Contact

For questions or collaboration:
**Mohammed Al-Robae**  
Email: moalrobae@gmail.com  


---

## 📌 License

This project is open source and available under the [MIT License](LICENSE).
