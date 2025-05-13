# CS3121 - Online Purchase Intentions During Crises

## Group Details

- **Project Group Name**: [Project Group 13]

- **Members**: (need to assign)
  - Member 1: [Name] - Data Preprocessing Lead
  - Member 2: [Name] - EDA and Insights Lead
  - Member 3: [Name] - Given Hypotheses Testing
  - Member 4: [Name] - Custom Hypotheses Testing
  - Member 5: [Name] - Rule Mining & Report Coordination

---

## Project Overview

This project explores the factors influencing consumers' intentions to make online purchases during crises in Sri Lanka. Using survey data (836 responses), we perform data preprocessing, exploratory analysis, hypothesis testing, and rule mining to derive actionable insights for Wolt's marketing strategies.

---

## Folder Structure

```
/OnlinePurchaseIntention/
│
├── README.md
├── requirements.txt
├── data/
│   └── responses.xlsx
├── preprocessing/
│   └── data_cleaning.ipynb
├── da_eda/
│   └── descriptive_analysis_and_EDA.ipynb
├── hypothesis_testing/
│   ├── given_hypotheses.ipynb
│   └── custom_hypotheses.ipynb
├── rule_mining/
│   └── apriori_rules.ipynb
└── output/
    ├── final_cleaned_data.csv
    ├── graphs/
    ├── hypothesis_results/
    └── rules_summary.txt
```

---

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/InduwaraRathnayake/CS3121-OnlinePurchaseIntention.git
```

### 2. Set Up Virtual Environment or Use Google Colab

```bash
python3 -m venv venv
source venv/scripts/activate 
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run Notebooks

- Navigate to the relevant folders (preprocessing, eda, etc.)
- Open Jupyter Notebook or VS Code
- Run the `.ipynb` files

---

## Deliverables

- **Final Report** (Max 10 Pages)
- **Video Presentation** (Max 2 Minutes)

---

## Key Tasks

- Data Cleaning and Transformation
- Descriptive and Exploratory Data Analysis (EDA)
- Hypothesis Testing (Given + Custom)
- Rule Mining using Apriori Algorithm
- Reporting Insights, Recommendations, and Conclusions

---

## Notes

- **Submission Deadline**: 14 May 2025, 11:59 PM
- Ensure all members are present in the video.
- Keep track of word/page limits for the report.

---

## References

- Pandas Documentation: https://pandas.pydata.org/docs/
- Cronbach's Alpha: https://en.wikipedia.org/wiki/Cronbach%27s_alpha
- Apriori Algorithm: https://en.wikipedia.org/wiki/Apriori_algorithm