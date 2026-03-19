# 🏦 Banking Dashboard — EDA & Power BI Analytics

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)

---

## 📌 Project Overview

This project presents a **comprehensive banking analytics solution** combining **Exploratory Data Analysis (EDA) in Python** with an interactive **Power BI Dashboard**. The goal is to uncover insights about clients, loans, deposits, and business lending across different demographics and banking relationships.

---

## 📊 Dashboard Pages

The Power BI report consists of **4 interactive pages**:

### 🏠 Home
- Overview of key KPIs
- Navigation to all report sections
- Highlights: **3,000 Total Clients**, **4.38bn Total Loan**, **3.77bn Total Deposit**, **963.28M Checking Accounts**, **698.73M Savings Accounts**, **2.60bn Business Lending**

### 🔵 Loan Analysis
- Breakdown by Banking Relationship (Commercial, Institutional, Private Bank, Retail)
- Bank Loan by Income Band, Occupation, Nationality
- KPIs: Total Loan **1.77bn**, Bank Loan **4.38bn**, Business Lending **2.60bn**, Credit Card Balance **9.53M**

### 🟢 Deposit Analysis
- Bank Deposit by Banking Relationship, Occupation, Nationality
- Deposit by Income Band
- KPIs: Total Deposit **3.77bn**, Bank Deposit **2.01bn**, Savings Account Amount **698.73M**, Checking Account AMT **963.28M**

### 📋 Summary
- Full client summary combining loan and deposit metrics
- Additional KPIs: Total Fees **158.19M**, Foreign Currency AMT **89.65M**, Engagement Account **17M**, Total CC Account **4K**

---

## 🐍 Python EDA Highlights

Exploratory Data Analysis was performed using Python before building the dashboard.

### Key Steps:
- **Data Loading & Cleaning** — Handling nulls, fixing dtypes, renaming columns
- **Univariate Analysis** — Distribution of loan amounts, deposits, income bands
- **Bivariate Analysis** — Loan vs. Occupation, Deposit vs. Banking Relationship
- **Demographic Insights** — Gender split, Nationality breakdown, Joining Year trends
- **Correlation Analysis** — Heatmaps of financial variables
- **Outlier Detection** — Boxplots for loan and deposit distributions

### Libraries Used:
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

---

## 📁 Project Structure

```
banking-dashboard/
│
├── data/
│   └── banking_data.csv          # Raw dataset
│
├── eda/
│   └── banking_eda.ipynb         # Jupyter Notebook — EDA Analysis
│
├── dashboard/
│   └── banking_dashboard.pbix    # Power BI Dashboard file
│
├── screenshots/
│   └── dashboard_preview.png     # Dashboard preview image
│
└── README.md
```

---

## 🔍 Key Insights

- 📈 **Business Lending** accounts for a significant share at **2.60bn**, reflecting strong commercial activity.
- 👥 Gender distribution is fairly balanced across the client base.
- 🏦 **Private Bank** clients contribute disproportionately to total loan volume.
- 💰 High-income bands dominate bank loan uptake, while mid-income bands lead in deposit volume.
- 🌍 Nationality segmentation reveals concentration in a few key regions.
- 📅 Client acquisition shows notable spikes in specific joining years (2015, 2018, 2021).

---

## 🚀 How to Use

### Power BI Dashboard
1. Download the `.pbix` file from the `dashboard/` folder.
2. Open it with **Power BI Desktop** (free download from Microsoft).
3. Use the year slicers (2013–2021) and filters (Gender, Banking Relationship, Institution Manager) to explore interactively.

### Python EDA
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/banking-dashboard.git
   cd banking-dashboard
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Launch the notebook:
   ```bash
   jupyter notebook eda/banking_eda.ipynb
   ```

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Data cleaning & EDA |
| Pandas | Data manipulation |
| Matplotlib / Seaborn | Visualizations |
| Power BI Desktop | Interactive dashboard |
| DAX | Calculated measures & KPIs |
| Power Query | Data transformation in Power BI |

---

## 📸 Dashboard Preview

![Banking Dashboard Preview](screenshots/dashboard_preview.png)

---

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for improvements to the EDA notebook or dashboard.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 👤 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [your-linkedin](https://linkedin.com/in/your-linkedin)

---

> ⭐ If you found this project helpful, please consider giving it a star!
