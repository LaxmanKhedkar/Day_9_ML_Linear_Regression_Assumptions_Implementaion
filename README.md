# 📊 Linear Regression Assumptions – Theory & Implementation

This repository contains a detailed walkthrough of **Linear Regression Assumptions**, including theory (slides/notes) and hands-on implementation in Python using Jupyter Notebook.

---

## 📌 Project Overview

Linear Regression is one of the most fundamental and widely used algorithms in machine learning. However, for it to work correctly, certain **assumptions** about the data must be met. This repository covers:

- **Theoretical Understanding** of Linear Regression assumptions  
- **Step-by-Step Implementation** using Python  
- **Visualization & Statistical Tests** for validating assumptions  

---

## 📚 Assumptions Covered

1. **Linear Relationship** – The relationship between independent and dependent variables should be linear.
2. **No Multicollinearity** – Independent variables should not be highly correlated with each other.
3. **Normality of Residuals** – The residuals (errors) should follow a normal distribution.
4. **Homoscedasticity** – The residuals should have constant variance across all levels of the independent variable.
5. **No Autocorrelation** – The residuals should not be correlated with each other (no pattern in errors).

---

## 🧠 Theory Highlights

📖 **Slides Summary** (from `Linear Regression Assumptions.pdf`):
- **Linear Relationship** → Tested using Pearson Correlation (R-value).
- **Multicollinearity** → Checked using Variance Inflation Factor (VIF > 5 indicates multicollinearity).
- **Normality of Residuals** → Tested using visual plots (Histogram/Distplot/Q-Q Plot).
- **Homoscedasticity** → Checked by plotting residuals vs predicted values.
- **Autocorrelation** → Checked using Durbin-Watson statistic or residual plots.

---

## ⚙️ Implementation Details

📓 **Notebook**: `Linear Regression Assumption-implementation.ipynb`

Key steps implemented:
- Load dataset and perform **Exploratory Data Analysis (EDA)**
- Check for **linearity** using correlation heatmaps & pairplots
- Compute **VIF** to detect multicollinearity
- Fit a **Linear Regression Model** and calculate residuals
- Plot **residual distribution** to check normality
- Plot **residuals vs predicted values** for homoscedasticity
- Check for **autocorrelation** using Durbin-Watson test

---


## 🚀 How to Run

1. Clone the repository  
```bash
git clone https://github.com/<your-username>/linear-regression-assumptions.git
cd linear-regression-assumptions

```
## 📈 Example Output

 Correlation Heatmap
 VIF Table
 Residual Distribution Plot
 Residuals vs Predicted Plot
 Durbin-Watson Statistic

These outputs help you verify if your data satisfies all regression assumptions.

## 🎯 Learning Outcomes

By the end of this project, you will be able to:
 Understand why assumptions are crucial in Linear Regression
 Perform statistical tests to validate assumptions
Improve model performance by addressing violations

## 🛠️ Tech Stack

- **Programming Language**: Python 🐍
- **Libraries Used**:
  - `pandas` – Data manipulation
  - `numpy` – Numerical computations
  - `matplotlib`, `seaborn` – Visualization
  - `statsmodels`, `scikit-learn` – Statistical modeling & regression

---

## 🏆 About the Author  

👨‍💻 **Laxman Bhimrao Khedkar**  
🎓 Computer Engineering Graduate | Aspiring Data Analyst / Data Scientist  

📧 **Email:** [khedkarlaxman823@gmail.com](mailto:khedkarlaxman823@gmail.com)  
🔗 **Portfolio:** [beacons.ai/laxmankhedkar](https://beacons.ai/laxmankhedkar)  
💼 **LinkedIn:** [linkedin.com/in/laxman-khedkar](https://www.linkedin.com/in/laxman-khedkar)  
🐙 **GitHub:** [github.com/Laxman7744](https://github.com/Laxman7744)  

--- 
### 📜 License

This project is open-source and available under the MIT License.
