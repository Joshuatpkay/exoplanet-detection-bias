# Exoplanet Detection Bias

## Project Overview

This project investigates whether currently discovered exoplanets represent a true sample of planetary systems or whether modern detection methods preferentially discover planets that are easier to observe.

Using observational data from the NASA Exoplanet Archive, this analysis compares transit and non-transit detection methods across:

- Orbital period
- Planet mass
- Planet radius
- Stellar temperature
- Distance to host stars
- Discovery trends over time

The project combines statistical hypothesis testing, exploratory data analysis (EDA), logarithmic scaling analysis, and trend modelling to examine how observational bias shapes our understanding of exoplanet populations.

---

## Dataset

This project uses the Planetary Systems Composite Table from the NASA Exoplanet Archive:

https://exoplanetarchive.ipac.caltech.edu/

Dataset accessed: May 2026.

---

## Technologies Used:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Google Colab / Jupyter Notebook

---

## Statistical Methods

The analysis includes:

- Kolmogorov-Smirnov testing
- Mann-Whitney U testing
- Spearman correlation analysis
- Log–log linear regression

---

## Key Findings

- Transit methods strongly favour short-period exoplanets.
- Non-transit methods detect proportionality more long-period planets.
- Observed exoplanet populations are heavily shaped by observational selection effects.
- Most confirmed exoplanets are concentrated within specific mass-period detection regions.
- Discovery rates increased dramatically during the Kepler mission era.

---

## Repository Structure

```plaintext
exoplanet-detection-bias/
|
|── data/
|── notebooks/
|── visuals/
|── .gitignore
|── README.md
└── requirements.txt
