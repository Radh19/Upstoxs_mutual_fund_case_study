
# Upstox Mutual Fund Experience Improvement: SIP Inflexibility & Feature Gap


## 📌 Problem Statement

Upstox users face significant friction when investing in mutual funds, specifically:

* Inability to **modify SIPs** (Systematic Investment Plans)
* No availability of **STP** (Systematic Transfer Plan) or **SWP** (Systematic Withdrawal Plan)
* Delays in execution with poor feedback and no tracking

This results in:

* High SIP cancellation rates
* Frustrated investors
* Loss of potential AUM and retention value

---

## 🎯 Objective

To investigate these issues using a Kaggle dataset and solve them by:

* Performing user behavior analysis
* Identifying pain points using data
* Proposing feature improvements backed by analytics
* Defining clear metrics to measure success

---

## 🧾 Dataset

Dataset: [Indian Mutual Fund Dataset (Kaggle)](https://www.kaggle.com/datasets/rajsaipainkra/indian-mutual-fund-dataset)

**Fields Used:**

* `User_ID`, `Fund_Name`, `SIP_Start_Date`, `Execution_Date`, `SIP_Amount`, `NAV_on_Date`, `Cancelled_Flag`, `Modified_Flag`, `Feedback_Score`, `Category`, `Expense_Ratio`

**Derived Columns:**

* `TAT_Days` = SIP Execution Date - SIP Start Date

---

## 📊 Key Insights

* **68% of users** who attempted to modify SIPs ended up cancelling them.
* **High TAT (3.6 days avg)** for fund execution — worst in debt and hybrid funds.
* **Poor feedback scores** directly tied to SIP failures or inability to modify.

---

## 💡 Recommendations

| Problem           | Insight                              | Recommendation                 |
| ----------------- | ------------------------------------ | ------------------------------ |
| Can't Edit SIP    | High post-modification cancellations | Launch SIP edit functionality  |
| No STP/SWP        | Demand from high-AUM users           | Add STP/SWP for advanced users |
| Delayed Execution | Poor experience, low ratings         | Add execution tracker + alerts |

---

## 📈 Success Metrics

* SIP Edit Adoption Rate
* % of SIPs executed in < 2 days
* Feedback Score improvement
* STP/SWP Feature Usage

---

---

## 📂 Files Included

* [`SIP_Case_Study_Product_Analyst.ipynb`](notebook/SIP_Case_Study_Product_Analyst.ipynb): Full EDA & analysis
* [`SIP_Product_Analyst_Case_Study.pptx`](presentation/SIP_Product_Analyst_Case_Study.pptx): Presentable insights deck

---

## 🧑‍💼 Author

**Radhika Patil**
Business & Product Analyst | Passionate about building user-centric experiences in fintech

---

## 🏷️ Tags

`Product Analyst` `Fintech` `Mutual Funds` `Kaggle` `EDA` `Feature Prioritization` `Upstox` `SIP` `SWP` `STP` `Retention` `Customer Feedback` `Data-Driven Product`

---

## ⭐ If you find this useful

Please star this repo and share feedback via issues or pull requests. 🙌
