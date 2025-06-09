# 💓 Heart Disease Prediction using Decision Tree

This project uses the **Decision Tree Classifier** to predict whether a person is likely to have heart disease or not, based on various health-related features.

> 📘 Designed for beginners — if you  a basic knowledge on GitHub, VS Code and know some Python, you can follow this easily!

---

## 📂 Dataset

The dataset used in this notebook is:
- File: `heart_disease.xlsx`
- Sheet: `Heart_disease`

It contains various medical parameters such as age, sex, cholesterol, etc., which are useful for predicting heart disease.

---
## 🛠️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn (for visualization)
- Scikit-learn (for ML model)
- Decision Tree Classifier

---

## 🚀 Workflow Overview

1. **Data Loading**  
   The data is loaded from an Excel file.

2. **Exploratory Data Analysis (EDA)**  
   Basic information and summaries of the dataset are displayed.

3. **Preprocessing**  
   - Label encoding for categorical variables  
   - Standard scaling for numerical features

4. **Train-Test Split**  
   Data is split into 80% training and 20% testing sets.

5. **Model Building**  
   A Decision Tree Classifier is trained on the dataset.

6. **Hyperparameter Tuning**  
   `GridSearchCV` is used to find the best parameters.

7. **Evaluation Metrics**  
   - Accuracy Score  
   - Confusion Matrix  
   - Classification Report  
   - ROC-AUC Score  
   - Decision Tree Plot

---

## 📊 Model Performance

The notebook includes:
- A comparison of performance before and after tuning
- Visualization of the decision tree for interpretability
- ROC-AUC for checking classifier strength

---

## 🖼️ Visualizations

- Heatmap of feature correlations
- Confusion matrix plot
- Decision tree diagram

---

## 📁 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. Make sure the Excel file `heart_disease.xlsx` is present in the same folder.

3. Open the notebook in Jupyter Notebook or VS Code and run all cells.

---

## 📌 Requirements

Install required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

---

## ✨ Author

Made with ❤️ by **Venu Krishna Chaitanya. P**  
Feel free to connect and contribute!
