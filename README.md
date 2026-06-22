# 📊 Telecom Customer Churn Analysis

> A comprehensive business analysis project identifying key drivers of customer churn in telecommunications and actionable retention strategies.

[![Python 3.8+](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/downloads/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/yashkumar3006/Business-Analysis-Telecom-Customer-Churn-Analysis-?style=social)](https://github.com/yashkumar3006/Business-Analysis-Telecom-Customer-Churn-Analysis-)

---

## 📋 Project Overview

This project analyzes customer churn data from a telecommunications company to identify patterns, trends, and critical factors affecting customer retention. Through data cleaning, exploratory data analysis (EDA), and customer segmentation, we generate **actionable business insights** to reduce churn and improve customer retention.

**Project Type:** Business Analyst Internship Project @ SaiKet Systems

---

## 🎯 Key Findings

| Finding | Impact |
|---------|--------|
| 📅 **Month-to-Month Contracts** | 42% higher churn rate vs. long-term contracts |
| 🆕 **New Customers (< 6 months)** | Critical churn window requiring immediate attention |
| 💰 **High Monthly Charges** | Strong positive correlation with churn probability |
| 📈 **Long-Term Customers (> 2 years)** | 90%+ retention rate |

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-----------|---------|
| **Python 3** | Data processing & analysis |
| **Pandas** | Data manipulation & cleaning |
| **NumPy** | Numerical computations |
| **Matplotlib** | Data visualization |
| **Seaborn** | Advanced statistical graphics |
| **Jupyter Notebook** | Interactive analysis & documentation |

---

## 📁 Project Structure

```
Business-Analysis-Telecom-Customer-Churn-Analysis/
├── README.md                          # This file
├── LICENSE                            # MIT License
├── CONTRIBUTING.md                    # Contribution guidelines
├── notebook/
│   └── Telecom_Churn_Analysis.ipynb  # Main analysis notebook
├── data/
│   └── telecom_churn.csv             # Dataset
└── images/
    ├── churn_distribution.png
    ├── contract_analysis.png
    ├── tenure_vs_churn.png
    ├── monthly_charges_analysis.png
    ├── correlation_heatmap.png
    └── customer_segmentation.png
```

---

## 📊 Analysis Performed

### 1. **Data Cleaning** 🧹
- Handled missing values
- Removed duplicates
- Standardized data formats
- Fixed inconsistencies in categorical variables

### 2. **Exploratory Data Analysis (EDA)** 🔍
- Churn distribution analysis
- Tenure vs. churn patterns
- Contract type impact on retention
- Monthly charges correlation study
- Customer demographics breakdown

### 3. **Customer Segmentation** 👥
- Segmented customers by risk level
- Identified high-risk customer profiles
- Analyzed segment-specific churn drivers
- Developed targeted retention strategies

### 4. **Visualizations** 📈
- Churn Distribution Charts
- Histograms & Boxplots
- Correlation Heatmap
- Contract Type Analysis
- Tenure-based Segmentation
- Service Usage Patterns

---

## 💡 Business Recommendations

| Strategy | Expected Impact | Priority |
|----------|-----------------|----------|
| 🎯 **Improve new customer onboarding** | Reduce early-stage churn | 🔴 High |
| 📋 **Offer incentives for long-term contracts** | Lock in revenue & improve loyalty | 🔴 High |
| 💬 **Personalized engagement for high-risk customers** | Targeted retention campaigns | 🟡 Medium |
| 📞 **Proactive support for high-charge customers** | Address pain points early | 🟡 Medium |
| 🎁 **Loyalty programs for long-term customers** | Recognize & reward loyalty | 🟢 Low |

---

## 🚀 Getting Started

### Prerequisites
```bash
python >= 3.8
jupyter >= 1.0.0
```

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yashkumar3006/Business-Analysis-Telecom-Customer-Churn-Analysis-.git
cd Business-Analysis-Telecom-Customer-Churn-Analysis-
```

2. Create a virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

5. Open `notebook/Telecom_Churn_Analysis.ipynb` and run the cells

---

## 📈 Key Metrics

- **Dataset Size:** 7,043 customers
- **Churn Rate:** 26.5%
- **Analysis Period:** Historic customer data
- **Features Analyzed:** 20+ customer attributes
- **Segments Identified:** 5 primary customer segments

---

## 📊 Visualizations Preview

### Churn Distribution
Shows overall churn vs. retained customers

### Contract Type Impact
Month-to-month contracts have significantly higher churn rates

### Tenure Analysis
Clear correlation: longer tenure = lower churn risk

### Monthly Charges Impact
Higher charges correlate with increased churn probability

### Correlation Heatmap
Identifies relationships between features and churn

### Customer Segmentation
5 distinct customer segments with unique risk profiles

---

## 🔄 How to Reproduce

1. Ensure you have the dataset in `data/telecom_churn.csv`
2. Open the Jupyter Notebook: `notebook/Telecom_Churn_Analysis.ipynb`
3. Run all cells in sequence (top to bottom)
4. Visualizations will be generated and saved to `images/` folder
5. Review insights in the notebook's final analysis cells

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes and test them
4. Commit with clear messages (`git commit -m "Add: new analysis"`)
5. Push to your fork (`git push origin feature/improvement`)
6. Open a Pull Request

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## 📝 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## 📧 Contact & Questions

**Yash Kumar**
- 🌐 GitHub: [@yashkumar3006](https://github.com/yashkumar3006)
- 💼 LinkedIn: [Yash Kumar Mathur](https://www.linkedin.com/in/yashkumarmathur)
- 📮 Have questions? Open an issue!

---

## 🙏 Acknowledgments

- Dataset source: Telecommunications industry
- Analysis framework: Business analyst best practices
- Internship mentor: SaiKet Systems

---

**Made with ❤️ for data-driven business decisions**
