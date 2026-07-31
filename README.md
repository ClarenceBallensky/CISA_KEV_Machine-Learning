# CISA Known Exploited Vulnerabilities Machine Learning
This repository contains my capstone portfolio for Codecademy's **Build a Machine Learning Model** skill path. 
Using the Cybersecurity and Infrastructure Security Agency's [Known Exploited Vulnerabilities (KEV) catalog](https://github.com/cisagov/kev-data), I developed three classification machine learning models: a logistic regression model, a random forest model, and a support vector machine model. I selected the models based on my findings in my [exploratory data analysis project](https://github.com/ClarenceBallensky/CISA_KEV_Analysis), which I completed on the same dataset. This project demonstrates data processing, model selection, model evaluation, and model refinement using Python.

## Model Performance Comparison
<img width="1096" height="592" alt="image" src="https://github.com/user-attachments/assets/8966f5be-5eb9-400a-8b5e-9bf989e857a6" />

*Figure 1. Comparison between the most successful versions of the logistic regression, random forest, and support vector machine models.*

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
- Scikit-learn
- Model selection
- Data processing
- Classification model implementation
- Jupyter Notebook
- Interpreting and communicating results

## Key Findings

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
7. Open `CISA_KEV_Machine-Learning.ipynb`.
8. Run all notebook cells from top to bottom.
