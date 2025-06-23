# Reducing No-Shows with Behavioural SMS Nudges

This project applied experimental A/B testing and statistical analysis to evaluate the impact of behavioural science-informed SMS messages on appointment attendance at Skinsmiths UK clinics.

## 🧠 Project Overview

- **Goal**: Reduce appointment no-show rates using a low-cost, ethical intervention.
- **Behavioural Components**: Personalisation and Reciprocity — tested independently and in combination to evaluate their effects on attendance behaviour.
- **Method**: Conducted controlled A/B experiments across clinics with multiple message variants.

## 📊 Key Outcomes

- **Up to 50% reduction in no-show rates** in some clinics.
- Improved booking efficiency, unlocked staff time, and increased revenue potential.
- Delivered measurable operational value **without relying on penalties or deposits**.
- Maintained a **frictionless and positive customer experience**.

## 🧪 Statistical Techniques

- **Chi-squared tests** for independence
- **Z-scores** to test proportions
- **One-sample t-tests** to compare changes in no-show rates against baseline
- **Confidence intervals** and descriptive statistics for effect size estimation

## 🛠️ Tools & Techniques

- **Languages**: Python
- **Libraries**: Pandas, NumPy, SciPy, Statsmodels, Seaborn, Matplotlib
- **Techniques**:
  - Experimental design (A/B testing with control and variant groups)
  - Behavioural science framing and message design
  - Exploratory data analysis and statistical testing
  - Comparative visualisations across clinic sites

## 📁 Repository Structure

```
project-root/
├── data/                         # Anonymised sample datasets
├── analysis/                     # Scripts for cleaning, visualisation, statistical tests
├── project_report.pdf            # Full write-up with methods, results etc
├── stakeholder_presentation.pdf # Slide deck for non-technical audience
├── README.md                     # Project overview (this file)
```

## 🔍 Future Improvements

- Expand behavioural message variations and test additional psychological nudges in reminders for missed appointmetns.
- Integrate real-time messaging and scheduling for dynamic nudging.
- Automate regular reporting dashboards using Power BI or Streamlit.

## 🛠️ Requirements

To replicate this analysis, install the following Python libraries:
# Data Management
import pandas as pd
import numpy as np

# Visualisation
import matplotlib.pyplot as plt
import seaborn as sns

# Statistical Analysis
from scipy import stats
from scipy.stats import chi2_contingency, ttest_1samp
from statsmodels.stats.proportion import proportions_ztest
import statsmodels.api as sm

# Utility
import warnings
import sys

## 📎 Disclaimer

All data is anonymised or simulated for demonstration. This project is based on real-world implementation but adapted for ethical sharing.

---

*This project demonstrates the intersection of behavioural science and data analytics to drive meaningful improvements in human-centred service design.*
