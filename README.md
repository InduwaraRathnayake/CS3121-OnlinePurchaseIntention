# CS3121 - Online Purchase Intentions During Crises

## Group Details

- **Project Group Name**: Project Group 13

## Project Overview

In this project, we analyze consumer behavior during crises in Sri Lanka, focusing on their intentions to make online purchases. Conducted on behalf of Wolt, a leading retail operator, our study utilizes 836 survey responses to examine how various psychological, social, and system-related factors influence online shopping decisions during crisis periods. Key components include data preprocessing, statistical analysis, hypothesis testing, and prescriptive rule mining using the Apriori algorithm.

---

## Project Report

<table>
  <tr>
    <td>
      <a href="https://github.com/InduwaraRathnayake/CS3121-OnlinePurchaseIntention/blob/a8ebab8822a70e333a3a3870ae7e6c5a374abff9/Project%20Group%2013.pdf">
        <img src="https://img.shields.io/badge/Project_Report-Click_to_View_PDF-blue?logo=adobeacrobatreader" alt="View PDF">
      </a>
    </td>
    <td>
      <a href="https://induwararathnayake.github.io/CS3121-OnlinePurchaseIntention/">
        <img src="https://img.shields.io/badge/Project_Report-Visit_our_site-yellow?logo=adobeacrobatreader" alt="Visit Our Site">
      </a>
    </td>
  </tr>
</table>



## Folder Structure

```
/OnlinePurchaseIntention/
│
├── README.md                         ← Project overview and instructions
├── requirements.txt                  ← Python package dependencies
│
├── data/
│   └── responses.xlsx                ← Raw survey data (836 responses)
│
├── preprocessing/
│   └── data_cleaning.ipynb          ← Missing values, duplicates, transformations, reliability checks
│
├── da_eda/
│   └── descriptive_analysis_and_EDA.ipynb  ← Descriptive statistics, visualizations, trend analysis
│
├── hypothesis_testing/
│   ├── given_hypotheses.ipynb       ← Hypothesis tests as per project brief
│   └── custom_hypotheses.ipynb      ← Additional hypotheses based on conceptual model
│
├── rule_mining/
│   └── apriori_rules.ipynb          ← Association rule mining using Apriori algorithm

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

## Key Tasks

| Task                      | Description                                                                                             |
| ------------------------- | ------------------------------------------------------------------------------------------------------- |
| **1. Data Preprocessing** | Cleaned dataset, handled missing values, calculated Cronbach's alpha for reliability                    |
| **2. EDA**                | Explored variable distributions, trends, outliers, and relationships using statistical and visual tools |
| **3. Hypothesis Testing** | Tested 10 given and 10 additional hypotheses using regression, correlation, mediation analysis          |
| **4. Rule Mining**        | Applied Apriori algorithm to extract 5 actionable rules from consumer behavior patterns                 |

---

## References

- Pandas Documentation: https://pandas.pydata.org/docs/
- Cronbach's Alpha: https://en.wikipedia.org/wiki/Cronbach%27s_alpha
- Apriori Algorithm: https://en.wikipedia.org/wiki/Apriori_algorithm
