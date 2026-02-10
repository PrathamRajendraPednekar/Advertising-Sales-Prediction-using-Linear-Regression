# 📈 Advertising Sales Prediction using Linear Regression

## 📌 Project Overview
This project aims to understand the relationship between advertising expenditure across different media channels (**TV, Radio, Newspaper**) and the resulting **Sales**.

By applying a **Linear Regression** model, the company can:
- Predict future sales based on advertising budgets
- Optimize ad spend allocation
- Improve strategic business decision-making

---

## 🎯 Problem Statement
The company wants to analyze how advertising investments in:
- TV
- Radio
- Newspaper

affect product sales, and use this understanding to **forecast sales** and **maximize return on investment (ROI)**.

---

## 🧠 Solution Approach
To solve this problem, a **Multiple Linear Regression** model was applied using historical advertising and sales data.

The model learns the relationship:


---

## 🛠️ Steps Taken

### 1️⃣ Data Loading & Exploration
- Loaded the dataset from a CSV file
- Checked data structure, shape, and summary statistics
- Verified data types and missing values

**Dataset Size:**  
- Rows: 200  
- Columns: 4  

---

### 2️⃣ Data Preprocessing
- Ensured all values were numerical
- No missing values found
- Selected features and target variable:
  - **Features:** TV, Radio, Newspaper
  - **Target:** Sales
- Split the dataset:
  - 80% Training Data
  - 20% Testing Data

---

### 3️⃣ Model Training
- Algorithm Used: **Linear Regression**
- Library: `sklearn.linear_model`
- Trained the model using training data

---

### 4️⃣ Model Coefficients
The trained model learned the following relationship:


📌 Interpretation:
- TV and Radio have the strongest impact on sales
- Newspaper has comparatively less influence

---

### 5️⃣ Model Evaluation

#### 📊 Metrics Used:
- **R-squared (R²)**
- **Root Mean Squared Error (RMSE)**

#### ✅ Results:
- **Training R²:** 90.70%
- **Testing R²:** 83.36%
- **RMSE:** 1.85

📌 These values indicate:
- Good model fit
- Strong predictive capability
- Low prediction error

---

### 6️⃣ Visualization
- Used a **heatmap** to visualize correlation between variables
- Observed strong correlation between:
  - TV & Sales
  - Radio & Sales

---

### 7️⃣ Prediction
- Predicted sales on test data
- Compared actual sales vs predicted sales
- Demonstrated how changing ad budgets impacts sales

---

## 📦 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 💼 Business Impact

### 📊 Sales Forecasting
- Helps predict future sales accurately
- Supports revenue planning

### 💰 Budget Optimization
- Identifies high-impact advertising channels
- Enables efficient allocation of ad spend

### 📈 Strategic Decision-Making
- Data-driven insights for marketing strategy
- Improved ROI and business outcomes

---

## ⚠️ Model Considerations

### Overfitting
- High accuracy on training data
- Poor performance on unseen data

### Underfitting
- Poor performance on both training and testing data

📌 This model shows **neither overfitting nor underfitting**, indicating a good balance.

---

## 🚀 How to Run the Project

### Step 1: Clone Repository
```bash
git clone <repository-url>


