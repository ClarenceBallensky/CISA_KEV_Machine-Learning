# CISA Known Exploited Vulnerabilities Analysis
This repository contains my capstone portfolio for Codecademy's **Data and Programming Foundations for AI** skill path. 
Using the Cybersecurity and Infrastructure Security Agency's [Known Exploited Vulnerabilities (KEV) catalog](https://github.com/cisagov/kev-data), I performed an exploratory data analysis to identify trends in known exploited vulnerabilities, remediation-timelines, and ransomware-associated weaknesses. This project demonstrates data cleaning, exploratory analysis, visualization, and interpretation using Python.

## Sample Visualisation
<img width="622" height="497" alt="image" src="https://github.com/user-attachments/assets/39353590-334e-4377-8817-3a85d2ce9eb4" />

*Figure 1. Top ten vendors by the number of vulnerabilities listed in CISA's Known Exploited Vulnerabilities (KEV) Catalog.*

## Research Questions
This project investigates the following research questions:
1. Which vendors have the greatest number of known vulnerabilities?
2. Which 3 common weakness enumerations (CWEs) occur most often?
3. Which 3 common weakness enumerations (CWEs) are most associated with ransomware?
4. How much time does CISA typically allow organizations to remediate known exploited vulnerabilities?
5. How much time does CISA typically allow organizations to remediate known exploited vulnerabilities in the case of a known randsomware campaign?
6. How has the number of exploited vulnerabilities changed over time?

## Skills Demonstrated
- Python 3
- Pandas
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Data visualization with Matplotlib and Seaborn
- Jupyter Notebook
- Interpreting and communicating analytical results

## Key Findings
- Microsoft has the largest number of cataloged vulnerabilities.
- Input validation and use-after-free are the most common weaknesses.
- Ransomware vulnerabilities show similar remediation timelines to the broader catalog.
- Most remediation deadlines are exactly 21 days.
- Vulnerability additions peaked in 2022.

## How to Run
### Required software:
- Jupyter Notebook
- Python 3
### Required packages:
```
pip install pandas
pip install matplotlib
pip install seaborn
pip install scikit-learn
pip install nltk
pip install beautifulsoup4
```
### Windows (Miniconda)
1. Clone this GitHub repository.
2. Install [Miniconda](https://www.anaconda.com/docs/getting-started/miniconda/main).
3. Open **Anaconda Prompt**.
4. Install Jupyter Notebook: `conda install jupyter`.
5. Install the dependencies listed above.
6. Launch Jupyter Notebook: `jupyter notebook`.
7. Open `CISA_Known_Exploited_Vulnerabilities_Analysis.ipynb`.
8. Run all notebook cells from top to bottom.
