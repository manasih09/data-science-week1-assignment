# Data Science Week 1 Assignment

**Organization:** WeIntern Pvt Ltd
**Objective:** In this assignment I cleaned an e-commerce dataset, analysed sales and customer behaviour, and presented my findings with charts and a report.

## Dataset description
I worked with the e-commerce customer behaviour dataset (`ecommerce_customer_behavior_dataset_v2.csv`).

- It has 17,049 orders and 18 columns, from 5,000 customers in 10 Turkish cities.
- The orders run from January 2023 to 25 March 2024.
- The fields include order and customer IDs, date, age, gender, city, product category, unit price, quantity, discount, total amount, payment method, device type, session duration, pages viewed, returning-customer flag, delivery time and customer rating.

## Tools and libraries used
Python, Jupyter Notebook, pandas, NumPy, Matplotlib and Seaborn (see `requirements.txt`).

## Key steps I performed
1. **Task 1: Data cleaning.** I inspected the raw data and checked for missing values (none found) and duplicates (none found). I validated the numeric and date fields and the categories, and created three new columns: `Order_Base`, `Order_Month` and `Delivery_Status`. I left the raw file unchanged and saved the cleaned file separately.
2. **Task 2: Sales analysis.** I calculated the main KPIs and analysed the monthly trend, city performance, delivery status, category performance over time and customer behaviour.
3. **Task 3: Visualizations.** I created bar, line and pie charts and a dashboard mockup, each with a short interpretation.
4. **Report.** I summarised the cleaning, analysis, findings, recommendations and limitations.

## Major findings
- The 17,049 orders generated about 21.78 million in revenue, with an average order value of 1,277.44.
- Electronics produces 48.13% of revenue from about 12% of orders. Sports sells the most units but is third in revenue.
- Monthly revenue is stable (about 1.31M to 1.59M). December 2023 is the peak, and Electronics drives most of the month-to-month changes.
- Istanbul, Ankara and Izmir generate about 52% of revenue. Istanbul leads because of order volume, not higher spending.
- Customers with 2 or more orders are 82.2% of customers and generate 95.1% of revenue. The top 10% of customers generate 38.81% of revenue.
- About one order in three is delivered in 8 days or more, but customer ratings are the same across delivery groups.

## Folder structure
```
data-science-week1-assignment/
├── data/
│   ├── raw/
│   └── cleaned/
├── notebooks/
│   └── week1_analysis.ipynb
├── outputs/
│   ├── charts/
│   └── dashboard/
├── reports/
│   └── final_report.pdf
├── screenshots/
├── README.md
└── requirements.txt
```

## How to run
1. Clone this repository.
2. Install the libraries with `pip install -r requirements.txt`.
3. Start Jupyter with `jupyter notebook`.
4. Open `notebooks/week1_analysis.ipynb` and choose Kernel > Restart & Run All. The notebook reads the raw file from `data/raw/` and saves the cleaned file in `data/cleaned/`.

## Author
- **Name:** Manasi Humbe
- **Role:** Data Science Intern, WeIntern Pvt Ltd
- **Email:** manasihumbe1234@gmail.com
