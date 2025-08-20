# Search Atlas Assessment - Data Scientist

## Overview

This repository contains my data science assessment for the Search Atlas Data Scientist Role

## Main File

**`src/jupyter_assessment.ipynb`** - This is the primary notebook file containing the complete assessment solution.

## Repository Structure

```
data/
├── iris.data       # Raw iris dataset
└── iris.names      # Dataset documentation

src/
├── __init__.py     # Source package initialization
└── jupyter_assessment.ipynb  # Primary assessment notebook
```

## Assessment Components

The notebook covers several key areas:

### 1. Data Loading and Exploration
- Loading the iris dataset using seaborn
- Initial data inspection and summary statistics
- Data structure analysis

### 2. Data Visualization
- Scatter plot analysis of sepal dimensions by species
- Species clustering visualization
- Statistical plotting with matplotlib and seaborn

### 3. Statistical Analysis
- Grouped statistical calculations (mean, median)
- Species-specific petal length analysis
- Data aggregation techniques

### 4. Algorithm Implementation
- Custom sorting algorithm implementation
- Fibonacci sequence generator
- Performance timing with magic commands

### 5. Jupyter Notebook Proficiency
- Magic command usage (%matplotlib inline, %time)
- Cell organization and documentation
- Inline visualizations

## Key Libraries Used

- **pandas** - Data manipulation and analysis
- **numpy** - Numerical computing
- **matplotlib** - Basic plotting
- **seaborn** - Statistical visualization
- **scipy** - Scientific computing

## Getting Started

1. Ensure you have Jupyter Notebook or JupyterLab installed
2. Install required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
3. Open the main notebook:
   ```bash
   jupyter notebook src/jupyter_assessment.ipynb
   ```

## Results Summary

The assessment demonstrates:
- Effective data visualization revealing distinct species clusters
- Proper statistical analysis of botanical measurements
- Clean, documented code with appropriate visualizations
- Understanding of both built-in and custom algorithm implementations

## Dataset

The analysis uses the classic iris dataset, which contains measurements of sepal and petal dimensions for three iris species: Setosa, Versicolor, and Virginica.
