# Claims analysis

## Project Description
This project analyzes healthcare claims data from a dataset that contains billing, provider information, diagnosis codes, and payer information. The analysis uses Python and pandas to perform exploratory data analysis, aggregations, and visualizations on three related datasets.

## Data Source Information
The project uses three csv files:
- Header: Contains provider information 
- Line: Contains service (procedure) information
- Code: Contains diagnosis codes

## How to Run the Notebook
1. Clone this repository in your local machine or google colab.
2. Ensure the three CSV files are in the same directory as the notebook or uploaded to your environment.
3. Open the Jupyter notebook or Google Colab notebook.
4. Run all cells sequentially from top to bottom.

## Summary of key findings
1. SB Internists has the highest amount of claims out of all the providers in the dataset leading with 152 claims.
2. Medicare is the biggest payer interms of claims leading with 62.37% of claims among all payers.
3. The most frequently appearing ICD-10 code is J96.01 with a frequency of 62. This code refers to Acute respiratory failure with hypoxia.
4. The most frequently appering HCPCS code is 99291 which stands for critical care service provided for the first initial hour.

## Required Libraries
```python
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```