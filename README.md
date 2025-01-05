# Disease-Insight

## Description
A Python program for exploring and visualizing an Alzheimer's dataset. It provides insights into deaths by age group, gender, race/ethnicity, causes of death, and correlations between causes. Users can interactively query and visualize the data through a command-line interface.

## Features
1. **Total Deaths by Age Group**: Bar plot visualization.
2. **Deaths by Gender**: Comparison of male and female deaths.
3. **Deaths by Cause**: Analysis and ranking of causes of death.
4. **Deaths by Race/Ethnicity**: Breakdown with color-coded bar plots.
5. **Correlation Between Causes of Death**: Heatmap visualization of correlations.

## How It Works
1. Load the dataset (`Alzheimers_dataset.csv`) using `pandas`.
2. Choose a query option from the menu to extract and visualize data.
3. Visualizations are generated using `matplotlib` and `seaborn`.

## Prerequisites
- Python 3.x
- Libraries: `pandas`, `matplotlib`, `seaborn`, `numpy`

Install the required libraries using:
```bash
pip install pandas matplotlib seaborn numpy
