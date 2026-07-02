# 📊 Marketing Campaign Performance Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a marketing campaign dataset containing **10,000 campaigns**. The objective is to analyze campaign performance across different marketing channels, evaluate Return on Investment (ROI), understand the customer conversion funnel, and identify actionable business insights to optimize marketing strategies.

---

## 🎯 Objectives

- Clean and preprocess the dataset.
- Analyze campaign performance across marketing channels.
- Compare marketing cost, revenue, and ROI.
- Perform conversion funnel analysis.
- Analyze monthly campaign trends.
- Identify relationships between campaign metrics.
- Generate business insights and recommendations.

---

## 📂 Dataset Information

The dataset contains **10,000 marketing campaigns** with the following features:

| Column | Description |
|---------|-------------|
| CampaignID | Unique campaign identifier |
| StartDate | Campaign start date |
| EndDate | Campaign end date |
| Channel | Marketing channel |
| Impressions | Number of ad impressions |
| Clicks | Number of clicks |
| Leads | Number of generated leads |
| Conversions | Number of successful conversions |
| Cost_USD | Campaign cost (USD) |
| Revenue_USD | Revenue generated (USD) |
| ROI | Return on Investment |

---

# 🧹 Data Cleaning

The following preprocessing steps were performed:

- Removed duplicate records
- Checked and handled missing values
- Converted `StartDate` and `EndDate` to datetime format
- Verified data types
- Created additional features:
  - Month
  - Campaign Duration

---

# 📈 Exploratory Data Analysis

The following analyses were performed:

### ✔ Dataset Overview
- Shape of dataset
- Summary statistics
- Data types

### ✔ Marketing Channel Analysis
- Campaign Distribution
- Total Cost by Channel
- Total Revenue by Channel
- Average ROI by Channel

### ✔ Conversion Funnel Analysis
- Total Impressions
- Total Clicks
- Total Leads
- Total Conversions
- Click Through Rate (CTR)
- Lead Conversion Rate
- Sales Conversion Rate

### ✔ Time Series Analysis
- Monthly Marketing Cost
- Monthly Revenue
- Monthly Average ROI

### ✔ Correlation Analysis
- Correlation Heatmap

### ✔ Additional Analysis
- Campaign Duration Distribution
- Cost vs Revenue Scatter Plot

---

# 📊 Visualizations

The project includes the following visualizations:

- Bar Charts
- Line Charts
- Horizontal Funnel Chart
- Scatter Plot
- Histogram
- Correlation Heatmap
- Count Plot

---

# 📌 Key Insights

- Identified the marketing channels with the highest ROI.
- Compared revenue generated across channels.
- Evaluated campaign spending efficiency.
- Measured customer conversion performance through the marketing funnel.
- Analyzed monthly trends in campaign performance.
- Studied relationships between marketing metrics using correlation analysis.

---

# 💡 Business Recommendations

- Increase investment in high-ROI marketing channels.
- Optimize low-performing campaigns before increasing budget.
- Improve landing pages to increase lead generation.
- Enhance sales conversion strategies.
- Continuously monitor monthly campaign performance to optimize future marketing investments.

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook



# 🚀 How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/Marketing-Campaign-EDA.git
```

2. Navigate to the project directory

```bash
cd Marketing-Campaign-EDA
```

3. Install the required libraries

```bash
pip install pandas numpy matplotlib seaborn
```

4. Launch Jupyter Notebook

```bash
jupyter notebook
```

5. Open `Marketing_Campaign_EDA.ipynb` and run all cells.

---

# 📌 Future Improvements

- Build an interactive Power BI dashboard.
- Create a Tableau dashboard.
- Develop machine learning models to predict campaign ROI.
- Build an interactive Streamlit web application.

---

# 👨‍💻 Author

**Anand Patel**

If you found this project useful, feel free to ⭐ the repository.
