# Marvel Cinematic Universe: Data-Driven Performance Analysis

**Course:** TEM 505 Data Driven Decision Making | **Arizona State University** | **Semester:** Fall 2025  
**Instructor:** Dr. Steve T Cho

## 👥 Authors
* **Apurva Annasaheb Dange**
* **Ankush Sanjay Harishchandre**

---

## 📌 Project Overview
This project investigates the financial and critical performance of the Marvel Cinematic Universe (MCU) to determine if the franchise is experiencing a statistically significant decline. By integrating financial data, audience responses, and critic ratings, this analysis provides data-driven insights for film studios and investors.

**Key Questions Addressed:**
1.  **Critical Factors:** What drives the success of Marvel movies?
2.  **Trend Analysis:** Is the "Marvel Era" of guaranteed success coming to an end?
3.  **Predictive Modeling:** Can we forecast which future films will be profitable?

## 🛠️ Technology Stack
* **IDE:** Jupyter Notebook
* **Language:** Python 3
* **Libraries:**
    * `Pandas` & `NumPy` (Data Manipulation)
    * `Matplotlib` & `Seaborn` (Visualization)
    * `Scikit-Learn` (Predictive Modeling/Regression)
    * `SciPy` (Statistical Testing)

## 📂 Files in Repository
* `data_analysis.ipynb`: The main Jupyter Notebook containing data cleaning, EDA, statistical tests, and modeling.
* `Marvel_Movies_Dataset.csv`: The dataset used for analysis (Profit, ROI, CinemaScore, etc.).
* `README.md`: Project documentation.

## 📊 Methodology

### 1. Data Preparation
We defined specific metrics to translate raw data into decision-useful information:
* **Profit:** `Worldwide Gross - Production Budget`
* **ROI:** `(Profit / Budget) * 100`
* **Score Standardization:** Converted CinemaScore grades (A+, B) into numerical values for regression analysis.

### 2. Statistical Testing (Welch’s T-test)
We compared **Pre-2021** vs. **Post-2021** releases to test for significant declines.
* **Result:** A p-value of **0.038** confirmed a statistically significant decline in critic scores.
* **Insight:** While profits have become volatile, the decline in quality (critic reception) is not just random fluctuation.

### 3. Predictive Modeling (Multiple Linear Regression)
We built a regression model to predict **Profit** based on Budget, Critic Score, and Audience Score.
* **Model Accuracy ($R^2$):** 0.66 (The model explains 66% of the variance in profit).

## 💡 Key Findings

### The "Budget Myth"
Our correlation analysis revealed that **Production Budget** has the weakest correlation with profit. Spending more on CGI/Production does not guarantee higher returns.

### The "Audience Factor"
**Audience CinemaScore** was identified as the strongest predictor of profit (Correlation: 0.66).
* *Business Implication:* Authentic customer satisfaction and word-of-mouth drive financial success more than marketing hype or budget size.

### Post-2021 Volatility
The MCU has shifted from a low-risk, stable asset (2008–2019) to a high-volatility asset (Post-2021). The "Marvel Brand" alone is no longer a mathematical guarantee of profitability.


## 📜 Conclusion
Our analysis suggests that for future success, studios must prioritize **script quality and audience satisfaction** over ballooning production budgets. Predictive modeling should be integrated into the script-approval and test-screening phases to mitigate the increased risk of volatility in the modern superhero market.

---
*Submitted on December 8, 2025*
