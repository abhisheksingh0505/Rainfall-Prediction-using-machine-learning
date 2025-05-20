
# 🌧️ Rainfall Prediction Using Machine Learning

A machine learning-based project analyzing and predicting rainfall trends across Indian sub-divisions using historical data from the Indian Meteorological Department (IMD). This model aids in agricultural planning and water resource management by providing more accurate rainfall predictions.

## 📌 Project Overview

India, being an agrarian country, relies heavily on monsoon rainfall. This project leverages machine learning algorithms to forecast rainfall using a historical dataset (1901–2017) from IMD. The models were tested to determine the most accurate method for predicting monthly and annual rainfall across 36 sub-divisions.

---

## 📁 Dataset

- **Source**: Indian Meteorological Department (IMD)
- **Period**: 1901–2017
- **Attributes**: Monthly and annual rainfall values for 36 Indian sub-divisions.
- **Format**: CSV file

> **Note**: Feature reduction and data preprocessing were applied to clean missing values and improve performance.

---

## 🧠 Models Used

- **Multiple Linear Regression (MLR)**
- **Random Forest Regression**
- **XGBoost Regression**
- **Lasso Regression**

Each model was evaluated using the **R² score** to measure accuracy.

---

## 📊 Results

| Model               | R² Score  |
|---------------------|-----------|
| Multiple Linear Regression | 0.9950    |
| Lasso Regression          | 0.9910    |
| XGBoost                   | 0.9819    |
| Random Forest             | 0.9737    |

> 🏆 **Best Model**: Multiple Linear Regression

---

## 🧪 Methodology

1. **Data Preprocessing**: Cleaning, handling missing values, outlier detection.
2. **Exploratory Data Analysis**: Correlation heatmaps, trend graphs, anomaly detection.
3. **Model Training**: Train/test split, hyperparameter tuning, feature engineering.
4. **Model Evaluation**: Using R² and residual analysis.
5. **Visualization**: Monthly correlation graphs, annual rainfall trends by region.

---

## 📌 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn)
- Jupyter Notebook
- CSV, DOCX for documentation
- Git & GitHub for version control

---

## 📝 Key Findings

- Eastern India receives significantly higher annual rainfall.
- June and July exhibit the highest monthly correlation.
- Machine learning models can provide reliable rainfall predictions with high accuracy, aiding agricultural planning.

---

## 📄 Research Paper

A detailed research paper titled _“Rainfall Prediction Using Machine Learning”_ is included in the repository for in-depth understanding of the methods, experiments, and results.

---

## 📚 References

1. Tiwari, N. et al. "A Novel Study of Rainfall in the Indian States..."
2. Suganya, B. et al. "Machine Learning based Rainfall Prediction..."
3. Mohammed, M. et al. "Prediction of rainfall using ML techniques..."
4. Ahmed, Y. et al. "Rainfall Prediction using MLR..."
5. Sowmya, V. et al. "Rainfall Prediction using ML & DL techniques..."

---

## 🤝 Contributing

Contributions are welcome! Please open issues or pull requests to discuss changes or suggest enhancements.

---

## 📬 Contact

For queries or feedback, contact:

- Vishal Pandey - [vishalpandey0266@gmail.com](mailto:vishalpandey0266@gmail.com)
- Abhishek Singh - [singh050530@gmail.com](mailto:singh050530@gmail.com)


