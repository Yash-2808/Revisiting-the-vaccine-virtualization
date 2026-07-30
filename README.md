# Revisiting the Vaccine Visualizations

## Overview

This project revisits historical vaccine-related disease incidence data and explores different visualization techniques to better understand the impact of vaccination programs. Using publicly available Polio and Measles datasets, the notebook recreates and improves visualizations originally discussed in the article *"Revisiting the Vaccine Visualizations"* by Randal S. Olson.

The goal is to demonstrate how effective data visualization can reveal trends, patterns, and the dramatic reduction of disease incidence following widespread vaccine adoption.

---

## Features

* Analysis of historical **Polio** incidence data (1928–1969)
* Analysis of historical **Measles** incidence data (1928–2003)
* Heatmap visualizations for identifying temporal patterns
* Line chart visualizations for trend analysis
* Median trend analysis with 95% confidence intervals
* Small multiples visualization for state-wise comparisons
* Data cleaning and preprocessing using Pandas
* Statistical summaries and visual insights

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Structure

```
.
├── Revisiting the vaccine visualizations.ipynb
├── data/
│   ├── POLIO_Incidence_1928-1969_20160304121200.csv
│   └── MEASLES_Incidence_1928-2003_20160304120254.csv
└── README.md
```

---

## Dataset

The project uses historical disease incidence datasets:

### Polio Dataset

* Time Period: 1928–1969
* Weekly reported cases across U.S. states

### Measles Dataset

* Time Period: 1928–2003
* Weekly reported cases across U.S. states

These datasets help illustrate disease prevalence before and after vaccine introduction.

---

## Visualizations Included

### 1. Heatmaps

Heatmaps display disease incidence across states and years, making it easier to identify outbreaks and long-term trends.

### 2. Line Charts

Aggregate yearly incidence is plotted to visualize changes in disease prevalence over time.

### 3. Median + 95% Confidence Interval

A statistical summary showing the median disease incidence along with variability across states.

### 4. Small Multiples

State-level trends are displayed in individual plots for easy comparison.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/revisiting-vaccine-visualizations.git
cd revisiting-vaccine-visualizations
```

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn notebook
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
Revisiting the vaccine visualizations.ipynb
```

---

## Running the Project

1. Ensure the datasets are placed inside the `data/` directory.
2. Open the notebook.
3. Run all cells sequentially.
4. Explore the generated visualizations and statistical summaries.

---

## Key Insights

* Disease incidence dropped significantly following vaccine introduction.
* Heatmaps reveal large-scale outbreaks before widespread vaccination.
* Aggregated trends clearly demonstrate the public health impact of vaccines.
* Different visualization techniques provide complementary perspectives on the same data.

---

## Learning Outcomes

This project demonstrates:

* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Statistical data summarization
* Effective visualization design
* Public health data interpretation
* Jupyter Notebook workflows

---

## Reference

Randal S. Olson, *Revisiting the Vaccine Visualizations*

Original article:
http://www.randalolson.com/2016/03/04/revisiting-the-vaccine-visualizations/

---

## License

This project is intended for educational and research purposes. Please ensure compliance with the original dataset and article licensing terms before redistribution.
