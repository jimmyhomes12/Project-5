# Project-5

## Overview

This repository contains a statistics-focused A/B testing project for an e-commerce landing page experiment.
The analysis evaluates whether a new page design improves conversion compared to the existing page.

## Main Project

- **Project:** `Statistics_Foundations/AB_Test_Ecommerce`
- **Notebook:** `Statistics_Foundations/AB_Test_Ecommerce/notebooks/01_ab_test_ecommerce.ipynb`
- **Report:** `Statistics_Foundations/AB_Test_Ecommerce/reports/ab_test_summary.md`

## Repository Structure

```text
Project-5/
├── README.md
├── Statistics_Foundations/
│   └── AB_Test_Ecommerce/
│       ├── README.md
│       ├── data/
│       │   └── ab_test_raw.csv
│       ├── notebooks/
│       │   └── 01_ab_test_ecommerce.ipynb
│       ├── reports/
│       │   ├── ab_test_summary.md
│       │   ├── ci_difference.png
│       │   └── conversion_rates.png
│       └── requirements.txt
├── ab_test.csv
└── countries_ab.csv
```

## Analysis Summary

- Randomized A/B test comparing `old_page` (control) vs `new_page` (treatment)
- Hypothesis test: one-tailed two-proportion z-test (`alpha = 0.05`)
- Result: no statistically significant improvement from the new landing page
- Recommendation: do not launch the new page based on current evidence

## How to Run

1. Install dependencies:

   ```bash
   pip install -r Statistics_Foundations/AB_Test_Ecommerce/requirements.txt
   ```

2. Open the notebook:

   ```bash
   jupyter notebook Statistics_Foundations/AB_Test_Ecommerce/notebooks/01_ab_test_ecommerce.ipynb
   ```

3. Review the written report:

   - `Statistics_Foundations/AB_Test_Ecommerce/reports/ab_test_summary.md`

## Notes

- The detailed project documentation is in:
  - `Statistics_Foundations/AB_Test_Ecommerce/README.md`
- Root-level files `ab_test.csv` and `countries_ab.csv` are included in the repository for reference data usage.
