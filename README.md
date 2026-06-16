# Iris Dataset Exploration and Visualization

## Overview

This project explores and visualizes the Iris dataset using Python. The goal is to understand the structure of the dataset, examine summary statistics, and identify patterns, distributions, and potential outliers through various visualizations.

## Objective

* Load and inspect the Iris dataset using Pandas.
* Analyze dataset structure and summary statistics.
* Visualize relationships between features.
* Understand data distributions and detect outliers.

## Dataset

The project uses the **Iris Dataset**, a well-known dataset in machine learning containing measurements of iris flowers from three species:

* Setosa
* Versicolor
* Virginica

### Features

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width
* Species

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn

## Tasks Performed

### 1. Data Loading

* Loaded the Iris dataset using Seaborn.
* Stored the dataset in a Pandas DataFrame.

### 2. Data Inspection

* Displayed the dataset shape.
* Printed column names.
* Viewed the first few rows using `head()`.
* Examined dataset information using `info()`.
* Generated summary statistics using `describe()`.

### 3. Data Visualization

#### Scatter Plot

* Visualized relationships between features.
* Used color coding to distinguish different species.

#### Histograms

* Displayed the distribution of numerical features.
* Observed feature spread and frequency.

#### Box Plots

* Identified potential outliers.
* Compared distributions across features.

## Key Findings

* The dataset contains 150 records and 5 columns.
* No missing values were found.
* Petal measurements provide strong separation among species.
* Feature distributions are generally well-behaved.
* Box plots help highlight variations and potential outliers.

## How to Run

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project folder:

```bash
cd <repository-name>
```

3. Install required libraries:

```bash
pip install pandas matplotlib seaborn
```

4. Run the notebook or Python script.

## Project Structure

```text
├── Iris_Visualization.ipynb
├── README.md
└── images/
    ├── scatter_plot.png
    ├── histogram.png
    └── boxplot.png
```

## Learning Outcomes

Through this project, I learned how to:

* Load datasets using Pandas and Seaborn.
* Explore dataset structure and statistics.
* Create visualizations using Matplotlib and Seaborn.
* Interpret relationships, distributions, and outliers in data.
* Perform basic exploratory data analysis (EDA), an essential step in machine learning workflows.

## Author

**Minahil Akhtar**
BS Computer Science Student | AI/ML Intern
