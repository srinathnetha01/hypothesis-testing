# Hypothesis Testing: Business Case Studies

**Goal:** Apply hypothesis testing to real business questions and connect statistical evidence to decisions.

## Business Problems Covered
1. Loan interest rates vs loan amount, length, and purpose  
2. Pricing consistency between experts  
3. Effect of reengineering on employee turnover & behavioral issues  
4. Software project prioritization impact on completion time  
5. Customer satisfaction & demographic/media insights

## Methods
- **t-tests** (independent/paired), **ANOVA**, **Chi-square**, basic EDA
- Tools: Python (Pandas, SciPy, Matplotlib) / Excel / R (choose what you used), Jupyter

## Repository Structure
```
data/         # datasets or sample snippets (DO NOT commit private or copyrighted data)
notebooks/    # analysis per problem (e.g., 01_loans.ipynb, 02_pricing.ipynb, ...)
results/      # plots and summary graphic (summary.png)
README.md
```

## How to Reproduce
1. Clone repo  
   ```bash
   git clone https://github.com/<your-username>/hypothesis-testing
   cd hypothesis-testing
   ```
2. Open notebooks in `notebooks/` and run cells (or view exported HTML/PDF in `results/`).

## Summary (Problem → Test → Insight)
| Problem | Test Used | Insight (1 line) |
|---|---|---|
| Loan rates vs length/purpose | ANOVA | [Your finding] |
| Pricing consistency (two experts) | Paired t-test | [Your finding] |
| Post-reengineering turnover/incidents | t-test | [Your finding] |
| Task priority vs days | ANOVA | [Your finding] |
| Satisfaction vs demographics/media | Chi-square | [Your finding] |

> Visual: see `results/summary.png`.

## Key Takeaway
**Hypothesis testing isn’t just statistics — it’s a bridge between data and business strategy.**

## Contact
Created by **Srinath Netha** • Connect on LinkedIn.
