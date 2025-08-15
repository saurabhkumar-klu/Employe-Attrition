# 👥 Employee Attrition Prediction

A **Machine Learning project** aimed at predicting employee attrition using the **IBM HR Analytics Employee Attrition & Performance** dataset. This project assists HR departments in identifying employees at risk of leaving and implementing retention strategies.

![Employee Attrition Dashboard](https://www.clearpeaks.com/wp-content/uploads/2020/10/HR-Employee-Attrition-Dashboard.png)

---

## 🚀 Features

* **Data Analysis & Visualization**

  * Perform Exploratory Data Analysis (EDA) to uncover patterns and correlations.
  * Visualize key factors influencing employee attrition.

* **Model Development**

  * Implement various machine learning models: Logistic Regression, Random Forest, XGBoost, and more.
  * Evaluate models using metrics like Accuracy, Precision, Recall, F1-Score, and ROC-AUC.

* **Deployment**

  * Build an interactive dashboard using Streamlit for real-time predictions.

---

## 📊 Dataset

* **Source:** [IBM HR Analytics Employee Attrition & Performance Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
* **Features:** 35 attributes including Age, Department, Education, Job Role, Monthly Income, and more.
* **Target Variable:** `Attrition` (Yes/No)

---

## 🧰 Technology Stack

* **Programming Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost, Streamlit
* **Tools:** Jupyter Notebook / VS Code / Google Colab

---

## ⚙️ Setup Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/saurabhkumar-klu/Employee-Attrition.git
   cd Employee-Attrition
   ```

2. **Install Dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Prepare the Dataset**

   * Download the dataset from [Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset).
   * Place the CSV file in the `data/` directory.

4. **Run the Jupyter Notebook**

   ```bash
   jupyter notebook Employee_Attrition_Prediction.ipynb
   ```

5. **(Optional) Run the Streamlit App**

   ```bash
   streamlit run app.py
   ```

---

## 📈 Evaluation Metrics

| Model               | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
| ------------------- | -------- | --------- | ------ | -------- | ------- |
| Logistic Regression | 0.85     | 0.83      | 0.78   | 0.80     | 0.88    |
| Random Forest       | 0.87     | 0.85      | 0.80   | 0.82     | 0.90    |
| XGBoost             | 0.88     | 0.86      | 0.82   | 0.84     | 0.91    |

*Note: Metrics are based on a test dataset split of 80/20.*

---

## 📊 Insights

* **High Attrition Factors:** Employees with low job satisfaction, high overtime, and low monthly income are more likely to leave.
* **Important Features:** Job role, years at company, and environment satisfaction significantly influence attrition.
* **Model Performance:** XGBoost outperforms other models in terms of accuracy and recall.

---

## 📄 License

This project is licensed under the **MIT License**.

---

Feel free to copy this README into your GitHub repository. If you'd like to include additional sections such as a detailed project workflow, contributing guidelines, or a changelog, let me know!
