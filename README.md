# 🏠 House Price Prediction

This repository contains a Jupyter Notebook that demonstrates **House Price Prediction** using various **Machine Learning regression models**.  
The project is based on the **California Housing Prices dataset**, which provides demographic and housing-related features for different districts in California.

---

## 📊 Dataset
- **Source**: California Housing Prices dataset (from the 1990 U.S. Census).  
- **Features include**:
  - Median Income
  - House Age
  - Average Rooms
  - Average Bedrooms
  - Population
  - Households
  - Latitude & Longitude
- **Target**: Median House Value

---

## 🚀 Models Used
The notebook experiments with several regression algorithms:
- Linear Regression  
- Polynomial Regression  
- Decision Tree Regression  
- Random Forest Regression  
- Gradient Boosting (XGBoost, LightGBM, CatBoost)  
- K-Nearest Neighbors  
- Logistic Regression (for categorical transformation if used)  
- Naive Bayes (for comparison in some preprocessing tasks)

Each model is evaluated using:
- **Mean Squared Error (MSE)**
- **R² Score**

---

## ⚙️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/<your-username>/house-price-prediction.git
cd house-price-prediction
pip install -r requirements.txt
```

---

## 📔 Usage
Open the notebook in Jupyter:

```bash
jupyter notebook House_Price_Prediction_Task_4.ipynb
```

Run all cells to:
1. Load and preprocess the dataset
2. Train multiple regression models
3. Compare results and visualize performance

---

## 📈 Results
- Models are compared based on **MSE** and **R² score**.  
- Random Forest and Gradient Boosting methods generally provide the **best performance** compared to linear models.  
- The notebook includes **visualizations** to analyze predictions vs actual values.

---

## 📌 Requirements
- Python 3.8+
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- scikit-learn
- xgboost, lightgbm, catboost

Install requirements:
```bash
pip install -r requirements.txt
```

---

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request.

---

## 📜 License
This project is licensed under the MIT License.
