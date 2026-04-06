# Luxury Consumer Behaviour in the Digital Era

### Segmentation, Loyalty Drivers, and Strategic Insights for Luxury Fashion Brands

## Overview

This project analyses how digital engagement shapes consumer loyalty in the luxury fashion sector. Using survey data from consumers interacting with leading luxury brands, the study combines data preparation, consumer segmentation, and regression analysis to identify behavioural patterns and evaluate the drivers of loyalty.

The project was developed as a capstone study at the intersection of consumer analytics, digital strategy, and data science.

## Business Problem

Luxury brands increasingly rely on digital channels to interact with consumers, yet digital interaction does not automatically translate into stronger loyalty or repeat purchase behaviour.

This project addresses three main questions:

* How can digital engagement in luxury fashion be measured?
* What consumer segments emerge from behavioural and attitudinal patterns?
* Which factors are most strongly associated with behavioural loyalty?

## Objectives

The analysis was designed to:

* construct indicators of digital engagement and loyalty
* segment consumers into meaningful clusters
* assess the drivers of behavioural loyalty through regression analysis
* generate insights relevant to luxury brand strategy and customer relationship management

## Repository Structure

```text
capstone-project/
├── data/              # raw and processed survey datasets
├── notebooks/         # methodology and analysis notebooks
├── results/           # figures, statistical summaries, and regression outputs
├── requirements.txt   # project dependencies
└── README.md
```

## Analytical Workflow

### 1. Methodology Notebook

**File:** `notebooks/Methodology.ipynb`

This notebook uses the raw dataset:

* `data/luxury_survey_raw.csv`

It covers the methodological stage of the project, including:

* data cleaning and preparation
* variable transformation
* index construction
* standardisation of selected variables
* consumer segmentation using clustering techniques

The output of this notebook is:

* `data/luxury_survey_with_clusters.csv`

This processed dataset is then used as the input for the second notebook.

### 2. Analysis and Results Notebook

**File:** `notebooks/Analysis_Results.ipynb`

This notebook uses:

* `data/luxury_survey_with_clusters.csv`

It contains the analytical stage of the project, including:

* descriptive analysis
* visualisation of key patterns
* correlation analysis
* cluster interpretation
* regression analysis
* generation of figures and statistical outputs stored in `results/`

## Key Insights

The analysis suggests that digital engagement is an important component of loyalty formation in luxury fashion, but its effect is not uniform across consumers.

Main findings include:

* digitally engaged consumers are not always the most behaviourally loyal
* consumer clusters differ substantially in both engagement intensity and loyalty outcomes
* emotional attachment appears to play an important role in explaining behavioural loyalty
* digital experience is most valuable when it strengthens brand connection, exclusivity, and perceived value

These findings highlight the importance of moving beyond visibility-focused digital strategies toward more differentiated consumer engagement models.

## Tools and Libraries

This project was developed in **Python** using the following libraries:

* pandas
* numpy
* matplotlib
* seaborn
* scipy
* scikit-learn
* statsmodels

## Installation

Install the required dependencies with:

```bash
pip install -r requirements.txt
```

## Files

### Notebooks

* `notebooks/Methodology.ipynb`
* `notebooks/Analysis_Results.ipynb`

### Data

* `data/luxury_survey_raw.csv`
* `data/luxury_survey_with_clusters.csv`

### Results

The `results/` folder contains:

* figures and charts
* regression outputs
* statistical summaries

## How to Use

1. Clone the repository.
2. Install the required libraries using `requirements.txt`.
3. Open `notebooks/Methodology.ipynb` in an environment that supports `.ipynb` files.
4. Run the notebook using `data/luxury_survey_raw.csv` as the input dataset.
5. Generate `data/luxury_survey_with_clusters.csv`.
6. Open `notebooks/Analysis_Results.ipynb`.
7. Run the notebook using `data/luxury_survey_with_clusters.csv` as the input dataset.
8. Review the outputs saved in the `results/` folder.

## Project Value

This project demonstrates the application of data science methods to a strategic marketing problem. It combines:

* survey-based consumer analytics
* clustering and segmentation
* regression modelling
* business interpretation for luxury brand strategy

## Author

**Almudena Poveda**
