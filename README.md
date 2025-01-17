# Exploratory Data Analysis With Python and Pandas

## Overview
This project demonstrates a comprehensive **Exploratory Data Analysis (EDA)** workflow on the Supermarket Sales dataset, using Python and libraries such as Pandas, NumPy, Matplotlib, Seaborn, and more. The notebook provides a step-by-step approach to understanding, visualizing, and analyzing the dataset, making it an ideal resource for data enthusiasts and professionals.

## Key Features

### Libraries Used
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical operations.
- **Matplotlib** and **Seaborn**: For visualizations.
- **calmap**: For calendar heatmaps.
- **ydata_profiling**: For automated dataset profiling.

### Dataset
- **Source**: [Supermarket Sales Dataset](https://www.kaggle.com/aungpyaeap/supermarket-sales)
- **File Used**: `supermarket_sales - Sheet1.csv`

### Analysis Workflow
1. **Initial Data Exploration**:
   - Loaded the dataset into a Pandas DataFrame.
   - Inspected the first few rows, column names, and data types.
   - Converted the `Date` column to a datetime format and set it as the index.
   - Displayed summary statistics using `df.describe()`.

2. **Univariate Analysis**:
   - Visualized the distribution of customer ratings using histograms and displots.
   - Marked key statistical indicators such as mean and percentiles.
   - Created count plots for categorical variables such as `Branch` and `Payment`.

3. **Bivariate Analysis**:
   - Explored relationships between variables using scatter plots, regression plots, and box plots.
   - Grouped data by date and calculated the mean of `gross income` for time series analysis.
   - Generated pair plots to analyze relationships between numerical variables.

4. **Dealing With Data Issues**:
   - Identified and handled duplicate rows.
   - Checked for missing values using heatmaps and imputed or dropped them as necessary.
   - Converted non-numeric data to numeric format where applicable.

5. **Automated Profiling**:
   - Used `ydata_profiling` to create an interactive profile report of the dataset.

6. **Correlation Analysis**:
   - Calculated correlation coefficients between numerical variables.
   - Visualized the correlation matrix using heatmaps.

## Visualization Highlights
- Histograms, scatter plots, and count plots for understanding data distributions.
- Regression plots to explore trends between key variables.
- Heatmaps for missing value analysis and correlation matrices.

## Requirements
To run the notebook, ensure the following:
- Python 3.x installed.
- Libraries: pandas, numpy, matplotlib, seaborn, calmap, ydata_profiling.
- The dataset (`supermarket_sales - Sheet1.csv`) downloaded from Kaggle.

## How to Use
1. Clone or download this repository.
2. Install the required libraries (`pip install -r requirements.txt`).
3. Run the Jupyter Notebook to explore the dataset and visualizations.

## License
This project is open for learning and development purposes. Feel free to modify and share it with proper attribution.

---
For any queries or issues, please reach out via the project's discussion section or contact the author directly.

