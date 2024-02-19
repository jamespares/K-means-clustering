# Country Categorisation Project (k-means clustering)

**Objective:**

Use machine learning to group countries based on their development status, using factors such as child mortality, economic indicators, and health statistics.
Data Source:

Help NGO (original source) provided the dataset.

**Features:**

child_mort: Child mortality rate (deaths under 5 per 1000 live births)
exports: Exports of goods and services (% of GDP)
health: Total health spending (% of GDP)
imports: Imports of goods and services (% of GDP)
income: Net income per person
inflation: Annual growth rate of total GDP
life_expec: Average life expectancy at birth
total_fer: Total fertility rate (children per woman)
gdpp: GDP per capita

**Methodology:**

**Data Exploration and Preprocessing:**

Examined data through descriptive statistics and visualizations.
Handled missing values.
Removed non-numeric features.
Analyzed feature correlations and created scatterplots.
Standardized data using MinMaxScaler.
K-Means Clustering:

Applied Elbow and Silhouette Score methods to select the optimal number of clusters (K).
Fit a K-Means model on the scaled data.
Assigned each country to a cluster based on its attributes.

**Evaluation:**

Calculated coefficient to assess clustering quality.

**Results:**

The analysis identified [specify the number here] distinct clusters of countries.
These clusters could be interpreted as "Developed" and "Less Developed" due to clear patterns in child mortality, inflation, and GDPP.

