# 📊 Lead Scoring Case Study

A machine learning model that assigns a lead score between 0–100 to help an 
education company (X Education) identify "Hot Leads" and improve their conversion 
rate from 30% to 80%.

## 🎯 Problem Statement

X Education sells online courses to industry professionals. Out of ~100 leads 
acquired daily, only ~30 convert to sales. The goal is to build a logistic 
regression model that scores each lead by conversion probability — so the sales 
team focuses effort on the most promising leads.

## ✨ Highlights

- **Lead scoring model** — assigns scores 0–100 per lead based on conversion likelihood
- **Target conversion rate** — model designed to help achieve 80% conversion
- **Feature selection** — identified key drivers of lead conversion
- **Business recommendations** — actionable insights for sales and marketing teams
- **Full summary report** included with findings and model interpretation

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas, NumPy | Data manipulation |
| scikit-learn | Logistic Regression, evaluation |
| Matplotlib, Seaborn | EDA and visualizations |
| Jupyter Notebook | Analysis and reporting |

## 📁 Project Structure
```
lead-scoring-case-study/
├── LEAD SCORING CASE STUDY(2).ipynb   # Main notebook
├── Leads.csv                           # Dataset
├── Summary Report - Lead Scoring Case Study.pdf  # Business report
├── LSCS_ppt (1).pdf                   # Presentation slides
└── README.md
```

## 📊 Approach

1. **EDA** — Explored lead sources, time spent on site, pages visited, prior activity
2. **Data Cleaning** — Handled missing values, dropped low-signal columns
3. **Feature Engineering** — Encoded categorical variables, scaled numeric features
4. **Modelling** — Logistic Regression with probability thresholding
5. **Evaluation** — Accuracy, Precision, Recall, ROC-AUC
6. **Lead Scoring** — Generated 0–100 scores from predicted probabilities

## 🔍 Key Findings

- **Time spent on website** is the strongest predictor of conversion
- Leads from **direct traffic** and **Google** convert at higher rates
- Leads who opened emails or clicked links are significantly more likely to convert
- Certain lead sources (e.g. landing page submissions) have very low conversion rates

## 📄 Dataset

The `Leads.csv` dataset contains ~9,000 leads with attributes including:
- Lead source, last activity, total time spent on website
- Email opened/clicked flags
- Country, occupation, specialization
- Target variable: `Converted` (1/0)

## ⚙️ Setup & Installation
```bash
# 1. Clone the repository
git clone https://github.com/Lanchana13/Lead-scoring-case-study.git
cd Lead-scoring-case-study

# 2. Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

# 3. Launch notebook
jupyter notebook "LEAD SCORING CASE STUDY(2).ipynb"
```

## 📄 License

MIT
