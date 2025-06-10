# Credit-Risk-Modelling

### Define Objectives & Questions

https://github.com/levist7/Credit_Risk_Modelling/tree/main?tab=readme-ov-file#technologies

- Formulate specific questions you want to answer (e.g., “Which factors drive customer churn?”).

Data Acquisition & Loading

Gather all relevant datasets (CSV, databases, APIs, etc.).

Load into your analysis environment (Pandas, R, SQL, etc.) and verify successful import.

Initial Data Inspection

Peek at the data structure: head(), info(), describe().

Note column types (numeric, categorical, datetime) and basic summary statistics.

Data Cleaning & Preprocessing

Missing Values: identify (isnull()), decide imputation or removal.

Duplicates: detect and drop exact or near-duplicates.

Data Types: convert strings to dates, factors to categories, etc.

Consistency Checks: uniform units, standardized labels.

Univariate Analysis

Numeric: histograms, boxplots, summary stats (mean, median, IQR).

Categorical: bar charts, frequency tables, mode.

Bivariate & Multivariate Analysis

Scatterplots for numeric–numeric relationships.

Grouped boxplots/violin plots for numeric–categorical.

Cross-tabs/heatmaps for categorical–categorical comparisons.

Feature Engineering & Transformation

Create new variables (ratios, interactions, time-based features).

Apply transformations (log, scaling, encoding) to normalize distributions.

Outlier & Anomaly Detection

Identify extremes via IQR, Z-scores or domain thresholds.

Decide whether to cap, transform, or remove outliers.

Correlation & Association Analysis

Compute correlation matrix for numeric features.

Use measures like Cramér’s V or Chi-square for categoricals.

Dimensionality Reduction (Optional)

Apply PCA or t-SNE to uncover latent structure or reduce noise.