# Mental Health Disorder Analysis (R Project) 🧠📊

## Overview
This project focuses on **analyzing mental health disorder data using R**.  
The analysis is performed on a **subset of 200 records** from a Kaggle mental health dataset and uses core R packages along with visualization tools to explore relationships, correlations, and statistical patterns in the data.

The project is intended for **academic learning, exploratory data analysis (EDA), and statistical understanding** of mental health-related datasets.

---

## Dataset Source
- **Dataset Name:** Mental Health Dataset  
- **Source:** Kaggle  
- **Link:** https://www.kaggle.com/datasets/imtkaggleteam/mental-health  
- **Records Used:** 200 (subset of the original dataset)

> ⚠️ The dataset has been subsetted to 200 records to keep the analysis lightweight and suitable for demonstrations and coursework.

---

## R Packages Used & Their Purpose

### 📦 Core R Packages
These packages come pre-installed with R and provide essential functionality:

- **base**  
  Fundamental R functions for data handling, arithmetic operations, and basic programming.

- **datasets**  
  Provides example datasets and supports structured data handling.

- **methods**  
  Supports object-oriented programming in R (S4 classes and methods).

- **stats**  
  Used for statistical computations such as:
  - Descriptive statistics  
  - Correlation analysis  
  - Hypothesis testing  

- **utils**  
  Utility functions for data import/export, file handling, and general support operations.

---

### 📊 Visualization Packages

- **graphics**  
  Used for creating basic plots such as:
  - Histograms  
  - Scatter plots  
  - Box plots  

- **grDevices**  
  Supports graphical devices and color handling, useful for exporting plots to files (PNG, PDF, etc.).

- **corrplot**  
  A specialized package for **visualizing correlation matrices**, used to:
  - Identify relationships between mental health variables  
  - Display correlation strength and direction visually  

---

## Analysis Performed
- Data loading and preprocessing  
- Summary statistics of mental health indicators  
- Correlation analysis between variables  
- Visual exploration using plots and correlation heatmaps  

---

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/mental-health-disorder-analysis.git
   ```

2. Open R or RStudio and install required packages (if needed):
   ```r
   install.packages("corrplot")
   ```

3. Load the dataset and run the R scripts or notebooks included in the repository.

---

## Project Structure
```
├── data/
│   └── mental_health_subset.csv
├── scripts/
│   └── analysis.R
├── results/
│   └── plots/
└── README.md
```

---

## Disclaimer ⚠️
This project is **for educational and research purposes only**.  
It does **not provide medical advice, diagnosis, or treatment**.

---

## License
This project is licensed under the **MIT License**.

---

## Acknowledgements
- Kaggle and IMT Kaggleteam for providing the dataset  
- R Core Team and package contributors  
