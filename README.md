# Developer Technology Trends — Analytics Capstone

This repository contains notebooks and presentation artifacts from an end-to-end analytics capstone exploring developer technology trends. The stated questions include which programming languages, databases, and IDEs are most used or in demand.

## Project workflow

1. **Collect data.** Use the job-data API and web-scraping notebooks in `Data collection/`, alongside the developer-survey data described in the original project materials.
2. **Clean records.** Work through duplicate detection, missing-value review/imputation, and outlier checks in `Data Cleaning/`.
3. **Wrangle and explore.** Normalize data, inspect distributions, and examine correlations in the `Data Wrangling/` and `EDA/` notebooks.
4. **Visualize.** Build charts in the visualization notebooks and review the Cognos Analytics dashboard PDF.
5. **Report.** Present the project findings in `Reporting/Presentation.pdf`.

The repository is organized by stage rather than as a single runnable application. The notebooks are learning/analysis artifacts; source datasets and a unified dependency/setup file are not present in the current repository tree. A fresh run may require downloading the relevant datasets and installing notebook dependencies separately.

## Repository structure

```text
Data-Analytics-Capstone-Project-/
├── Data collection/
│   ├── Collecting_Jobs_data_Using_API-Questions.ipynb
│   └── Web-Scraping-Lab.ipynb
├── Data Cleaning/
│   ├── Hands-on Lab Finding Duplicates_v2.ipynb
│   ├── Hands-on Lab 7 Removing Duplicates_v2.ipynb
│   ├── Hands-on Lab 8 Finding Missing Values.ipynb
│   ├── Hands-on Lab 9 Imput Missing Values.ipynb
│   └── Lab 12 Finding Outliers.ipynb
├── Data Wrangling/
│   ├── M2DataWrangling-lab-v2.ipynb
│   └── Hands-on Lab 10 Normalizing Data.ipynb
├── EDA/
│   ├── M1ExploreDataSet-lab-V2-v1.ipynb
│   ├── Hands-on Lab Exploratory Data Analysis.ipynb
│   ├── Lab 11 Finding How The Data is Distributed.ipynb
│   └── Lab 13 Finding Correlation.ipynb
├── Visualization/
│   ├── visualization and charting notebooks
│   └── Dashboard by Cognos Analytics.pdf
├── Reporting/
│   └── Presentation.pdf
└── README.md
```

The Visualization folder contains separate notebooks for general charts, box plots, scatter plots, bubble plots, pie charts, stacked charts, line charts, and bar charts.

## Outputs

- [Cognos Analytics dashboard PDF](Visualization/Dashboard%20by%20Cognos%20Analytics.pdf)
- [Project presentation](Reporting/Presentation.pdf)

The README describes Stack Overflow Developer Survey data and job-posting data as sources. The current repository tree contains notebooks and PDF artifacts but no source CSVs; confirm the dataset and survey version before reproducing results.
