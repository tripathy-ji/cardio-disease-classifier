
# 🫀 Cardiovascular Disease Risk Prediction

This project uses machine learning ensemble techniques to classify the risk of cardiovascular disease using medical and lifestyle features. It includes preprocessing, SMOTE balancing, model stacking, and detailed performance analysis.

---

## 📦 Dataset

- **Source:** [Kaggle - Cardiovascular Disease Dataset](https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset)
- **File:** `cardio_train.csv`
- **Samples:** 70,000+ labeled records
- **Features:** Age, Gender, Height, Weight, Blood Pressure, Cholesterol, Glucose, Smoking, Alcohol, Physical Activity, etc.

---

## 🧠 Models Used

- **Random Forest**
- **XGBoost**
- **Neural Network (MLPClassifier)**
- **Stacking Classifier** for final ensemble

All models are optimized and trained with `tqdm` tracking and `SMOTE` to handle class imbalance.

---

## 📈 Performance

| Metric        | Score   |
|---------------|---------|
| Accuracy      | 72.4%   |
| ROC-AUC Score | 79.7%   |
| Confusion Matrix | `[[5190 1734], [2132 4953]]` |

---

## 🔧 Features

- ✅ Full training pipeline in **Colab**
- ✅ **KaggleHub** integration to pull datasets
- ✅ Class balancing with **SMOTE**
- ✅ Ensemble learning with **StackingClassifier**
- ✅ Live progress tracking with `tqdm`
- ✅ Reproducible and extendable code

---

## 📂 File Structure

```
.
├── cardiovascular_model.ipynb       # Full Colab notebook
├── best_nn_model.keras              # Saved NN model
├── model.pkl / rf_model.pkl         # Other model files
├── kaggle.json                      # (Optional) Kaggle API credentials
├── README.md                        # Project documentation
```

---

## 🧪 Sample Prediction

The final model returns binary classification:

- **0** → Low Risk
- **1** → High Risk

Example Output:
```
Prediction: HIGH risk
```

---

## 🚀 How to Run

1. Upload your `kaggle.json` file to Colab
2. Run the notebook `cardiovascular_model.ipynb`
3. Modify `predict_risk(sample_data)` for your custom inputs

---

## 📜 License

MIT License. See `LICENSE` for more details.

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## 📬 Contact

Made with ❤️ by [Your Name](https://github.com/your-username)
