# 🎮 ABC Gaming Platform Analytics - Case Study

Welcome! This repository contains my analysis and solution for the analytics case study assigned by ABC — a real-money online gaming platform. The task was to understand user behavior based on gameplay, deposits, and withdrawals, and score users using a point-based system.

---

## 🧠 Objective

The goal is to analyze user data to:

- Understand engagement through gameplay activity
- Analyze monetary behavior (deposits and withdrawals)
- Score users based on defined formulas
- Deliver business insights and actionable recommendations

---

## 📦 Dataset Details

The Excel file includes the following sheets:

| Sheet Name        | Description |
|------------------|-------------|
| **User Gameplay** | Number of games played by users over time |
| **Deposit Data**  | User-wise deposit transactions |
| **Withdrawal Data** | User-wise withdrawal transactions |

---

## 🔧 Tools Used

- **Language**: Python (Pandas, NumPy)
- **Notebook**: Jupyter
- **Visualization**: Matplotlib / Seaborn (optional)
- **File Format**: Excel

---

## 🛠️ Approach

### 1. Data Cleaning
- Removed empty rows and fixed headers
- Converted columns to correct data types (especially dates)
- Standardized column names

### 2. Exploratory Data Analysis (EDA)
- Total games played per user
- Total and average deposit amounts
- Total withdrawals
- Time-based trends in deposits and gameplay

### 3. Points Calculation

| Action        | Formula                        |
|---------------|--------------------------------|
| Deposit       | `Points = 0.01 * Deposit Amount` |
| Gameplay      | `Points = 1 * Games Played`      |

> Total Points = Deposit Points + Game Points

### 4. User Scoring
- Combined all calculations into a user-level summary
- Ranked users based on total points

### 5. Insights
- Identified top performing users
- Detected user trends and behaviors
- Compared deposits vs withdrawals

---

## 📈 Sample Insights

- 20% of users contribute over 80% of deposits
- Peak gameplay hours are between 6 PM - 10 PM
- A few users play a lot but don’t deposit — potential upsell target
- High-value users also have higher withdrawal volumes

---

## 📋 Recommendations

- 💸 Introduce tier-based rewards for high depositors
- 🎁 Incentivize gameplay through challenges and bonus rounds
- 📢 Retarget highly active non-depositing users with offers
- ⏰ Launch weekend or evening promotions based on usage trends

---

## 📂 Files in This Repo

| File Name                        | Description |
|----------------------------------|-------------|
| `ABC_Gaming_Case_Study.ipynb`    | Main notebook with full analysis |
| `Analytics Position Case Study.xlsx` | Provided dataset |
| `README.md`                      | Project overview |
| `summary.csv` _(optional)_       | Final user score summary |

---

## 🙋 About Me

I’m a Data Analyst passionate about uncovering patterns, driving business insights, and creating data-powered strategies. Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/mdajams) or check out more projects on [GitHub](https://github.com/MdAjams).

---

## 🚀 Final Note

Thanks for the opportunity to work on this exciting challenge! I’ve ensured the entire analysis is transparent, reproducible, and business-oriented. Looking forward to discussing the results with your team 😊

