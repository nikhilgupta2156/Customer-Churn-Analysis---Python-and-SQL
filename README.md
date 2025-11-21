
---

# 📊 **Customer Churn Analysis & Revenue-at-Risk Modeling**

*A Data Analytics Case Study using Python & SQL*

---

## 🎯 **Objective**

Understanding customer churn is one of the most crucial challenges for subscription-based companies. This project aims to explore **why customers leave**, identify **high-risk churn segments**, and quantify the **revenue impact of churn** using a combination of Python, SQL, and analytical KPIs.

### **Why customers churn (what we explored):**

* High monthly charges
* Short-term (Month-to-month) contracts
* Lack of Tech Support or Online Security
* High dependency on Fiber Optic services
* Senior citizen behavior
* Billing preferences such as Electronic Checks or Paper Billing

### **Business KPIs & Metrics examined:**

* **Churn Rate (Overall & segmented)**
* **Retention Rate**
* **Tenure-based churn patterns**
* **Revenue at Risk (RAR)**
* **Expected Revenue Loss**
* **Customer Lifetime Value (CLV)**
* **Average Revenue Per User (ARPU)**
* **Segment-wise Churn Lift**
* **High-value customer risk**

By combining analytical techniques with business understanding, this project reveals **which customers are most likely to churn, why they churn, and how much revenue is at risk** if no action is taken.

---

## 📂 **Dataset Description**

**Source:** IBM Telco Customer Churn Dataset
**Records:** ~7,000+ customers
**Features:** Demographics, contract type, billing information, service usage, churn label

### **Data Preprocessing Done**

* Fixed incorrect data types (e.g., `TotalCharges`)
* Removed duplicates
* Handled missing values
* Standardized categorical columns
* Created new features for segmentation and revenue analysis

---

## 🛠️ **Methodology & Tools Used**

### **Approach**

* Exploratory Data Analysis (EDA)
* Customer segmentation & profile creation
* Churn KPI calculation
* Revenue risk estimation using SQL
* Business insights and retention strategy recommendations

### **Tools Used**

* **Python** (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
* **SQL** (CTEs, Group Aggregations, Revenue Modeling)
* **SQLite & `pandas.read_sql_query()`**
* **Jupyter Notebook / Google Colab**
* **GitHub for version control**

---

## 📐 **Metrics & KPIs Used in This Project**

*All metrics below were computed using Python & SQL in the notebook.*

---

### **1. Churn Metrics**

* Overall churn rate
* Churn segmented by:

  * Gender
  * Senior Citizen
  * Partner / Dependents
  * Contract Type
  * Internet Service
  * Phone Service
  * Multiple Lines
  * Payment Method
  * Paperless Billing
  * Online Security / Tech Support
* Tenure-based churn rate (0–72 months)

---

### **2. Revenue & Financial Metrics**

* Average Monthly Charges (Python & SQL)
* Average Total Charges
* **Revenue at Risk (RAR)**
* **Expected Revenue Loss per segment**
* High-value customers contributing to maximum risk
* MonthlyCharges vs Churn comparison
* TotalCharges vs Churn comparison

> **Key Insight:**
> About **30% of MonthlyCharges revenue is at risk** due to churn-prone segments.

---

### **3. Customer Value Metrics**

* **Customer Lifetime Value (CLV)** estimation
* High-value churn-prone cohorts
* Customer segmentation & lift score:

  * 6 high-risk customer profiles
  * Churn rates ranging **40%–82%**
  * Lift values **2.0×–3.1×** baseline churn

---

### **4. SQL-Based KPIs**

* Category-wise churn counts
* Average billing metrics by churn
* Tenure comparison (churn vs non-churn)
* Service-specific churn patterns
* Weighted revenue loss estimates
* Expected revenue loss for upcoming month

---

## 👥 **Customer Segmentation (6 High-Risk Profiles)**

Using Python filtering and business rules, six churn-prone segments were created, such as:

1. **Fiber Optic users with high monthly charges**
2. **Customers without Online Security / Tech Support**
3. **Electronic check users**
4. **Senior citizens with no Tech Support**
5. **Low-tenure users (<6 months)**
6. **Female partner-dependent behavior profiles**

Each profile was evaluated for:

* Churn Rate
* Lift
* Revenue impact
* Priority ranking

---

## 📈 **Analysis & Key Results**

### 🔍 **Major Insights**

* **Month-to-month contract customers churn ~3× more.**
* **Customers without Tech Support churn ~45% more.**
* Fiber Optic users show significantly higher churn.
* High Monthly Charges correlate strongly with churn.
* Paperless billing & Electronic Checks show increased churn.

### 💸 **Revenue Impact**

* **30% of MonthlyCharges revenue is at risk.**
* High-ARPU customers create **4× more revenue loss** despite being fewer in number.
* SQL-based RAR modeling highlights financially vulnerable customer cohorts.

### 🎯 **Business Recommendations**

* Push long-term contracts
* Improve Tech Support onboarding
* Create retention offers for high-value churn risks
* Target low-tenure customers early
* Review pricing for Fiber users

---

## ▶️ **Getting Started**

### **Requirements**

* Python 3.x
* Install dependencies:

```bash
pip install -r requirements.txt
```

### **Run the Project**

```bash
git clone <your-repo-url>
cd customer-churn-analysis
google colab notebook
```

Open:

```text
Customer_Churn_Analysis.ipynb
```


---

## 🚀 **Future Improvements**

* Build ML churn prediction model
* Add Power BI / Tableau dashboards
* Deploy a Streamlit churn prediction app
* Automate monthly revenue-risk reports

---

## 📬 **Contact**

**Name:** *NIKHIL GUPTA*
**Email:** *nikhilgupta2156ng@gmail.com*
**LinkedIn:** *linkedin.com/in/nikhilgupta2156*
**GitHub:** *https://github.com/nikhilgupta2156*

**Acknowledgements:** IBM Telco Customer Churn Dataset

