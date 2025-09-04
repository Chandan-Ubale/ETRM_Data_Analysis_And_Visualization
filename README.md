# Data Analysis and Visualization

## Overview

This project demonstrates end-to-end **data analysis and visualization** workflows using multiple data formats. The notebook covers data ingestion, preprocessing, and exploratory data analysis (EDA) with meaningful insights into commodity trade data.

## Features

* **Data Ingestion:** Load data from CSV, JSON, Excel, TXT, HTML, and XML into Pandas DataFrames.
* **Data Preprocessing:**

  * Ensure consistency across datasets by verifying column names and data types.
  * Convert `DeliveryStart` and `DeliveryEnd` columns into datetime format.
* **Exploratory Data Analysis (EDA):**

  * Average price per commodity.
  * Trade volume comparisons.
  * Distribution and trend analysis.
* **Visualization:**

  * Heatmaps, bar charts, and trend plots to highlight insights.

## Technologies Used

* **Python 3.x**
* **Pandas** – data manipulation and analysis
* **Matplotlib / Seaborn** – visualizations
* **NumPy** – numerical computations
* **Jupyter Notebook** – interactive environment

## Project Structure

```
├── DataAnalysisAndVisualization.ipynb   # Main notebook containing analysis and visualizations
├── data/                                # Folder containing raw datasets (CSV, JSON, Excel, TXT, HTML, XML)
└── README.md                            # Project documentation
```

## How to Run

1. Clone this repository:

   ```bash
   git clone https://github.com/Chandan-Ubale/ETRM_Data_Analysis_And_Visualization.git
   cd ETRM_Data_Analysis_And_Visualization
   ```
2. Install required packages:

   ```bash
   pip install pandas numpy seaborn matplotlib
   ```
3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook DataAnalysisAndVisualization.ipynb
   ```

## Results & Insights

* Commodities exhibit different trade behaviors (buy/sell patterns).
* Gas trades are dominated by **buy positions**, while coal trades lean towards **sell positions**.
* Price trends reveal market expectations and external influencing factors.


