# Electric Vehicle Data Analysis and Visualization

## Project Overview

This project involves the analysis and visualization of electric vehicle (EV) data to identify top-performing brands and provide actionable insights. The analysis was conducted using Jupyter Notebook for data processing and Power BI for visualization.

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- Power BI Desktop
- Python Libraries: pandas, numpy, matplotlib, seaborn

## Data Analysis

The data analysis was performed in a Jupyter Notebook. The key steps included:
1. **Importing Libraries and Data:** Loaded datasets using pandas.
2. **Initial Data Analysis:** Used functions like `describe()`, `info()`, and `shape` to understand the data structure.
3. **Data Preprocessing:**
   - Removed irrelevant columns.
   - Handled missing data by replacing missing values with median (numerical) and mode (categorical).
   - Conducted outlier analysis using box plots.
   - Normalized data using MinMaxScaler.
   - Encoded categorical variables using One-Hot Encoding.

## Visualization

### Jupyter Notebook Visualizations
- Box plots for outlier detection.
- Heatmap to visualize missing data.
- Bar plots to compare performance metrics across companies.

### Power BI Visualizations
- Bar charts to compare engine power, torque, speed, and range.
- Interactive dashboards with filters and slicers for dynamic data exploration.

## Key Findings

- **Best Performer:** Tesla emerged as the best company for electric vehicles based on battery range, engine power, torque, and charging infrastructure.
- **Recommendations for Other Companies:**
  - Improve battery range and engine power.
  - Enhance torque and overall vehicle performance.
  - Expand and improve the charging station network.

## Potential Benefits

1. **For Manufacturers:** Performance benchmarking and competitive analysis.
2. **For Policymakers:** Data-driven policy formulation and infrastructure development.
3. **For Consumers:** Informed purchasing decisions and improved user experience.
4. **For the EV Industry:** Market growth, sustainable development, and collaboration opportunities.
