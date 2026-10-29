# Analysis of the Distribution of Central-to-Regional Fiscal Transfers (TKDD) and Its Impact on the Human Development Index (HDI) in Indonesia in 2023

**Team BebasAja | Universitas Gadjah Mada**

Our team's notebook from the **first-place-winning project at the TECHFEST 2025 Data Analytics Competition**, exploring how Indonesia's regional fiscal transfers relate to human development across 38 provinces in 2023.

**[Read the competition notebook](EDA_BebasAja_UniversitasGadjahMada.ipynb)**

## Competition

TECHFEST Data Analytics was a national university competition organized by **HIMTI, BINUS University**, as part of Technology Festival 2025. Teams used Python and the organizers' dataset to investigate a public-policy case through exploratory data analysis, visualization, and evidence-based interpretation. The competition included a notebook-based preliminary round and a final round with a report and presentation.

This repository preserves the team's submission notebook, including its original Indonesian narrative, charts, and saved outputs.

## Project

**Analisis Distribusi TKDD dan Dampaknya terhadap Indeks Pembangunan Manusia (IPM) di Indonesia Tahun 2023**

The analysis examines **Transfer ke Daerah dan Dana Desa (TKDD)**, or regional and village fund transfers, alongside the **Indeks Pembangunan Manusia (IPM)**, Indonesia's Human Development Index. It investigates differences between allocated and realized transfers, regional disparities, and relationships with population, poverty, and economic indicators.

The notebook covers:

- Numeric-format cleaning, missing-value inspection, and median imputation by island group.
- Feature engineering for budget realization ratios, island groups, and transfers per capita.
- Descriptive statistics, outlier analysis, provincial comparisons, and a geographic visualization.
- Pearson correlation tests, principal component analysis (PCA), and K-means clustering supported by elbow and silhouette analysis.
- Interpretation of provincial patterns and public-policy recommendations.

## Selected findings

- Realized TKDD and IPM had a weak positive correlation (**r ≈ 0.23, p = 0.1578**) in the notebook's imputed dataset; the relationship was not statistically significant at the 5% level.
- Regional GDP per capita and TKDD per capita had a positive correlation (**r = 0.3341, p = 0.0404**).
- Provincial comparisons and clustering highlighted distinct fiscal and socioeconomic profiles, motivating recommendations tailored to regional conditions.

These are exploratory associations from a single year of provincial data, including imputed values. They do not establish a causal effect of transfers on human development.

## Contributors

**Team BebasAja - Universitas Gadjah Mada**

- [Farhan Adiwidya Pradana](https://github.com/Farscent)
- Deira Aisya Refani
- Gracella Wiendy Koesnadi
