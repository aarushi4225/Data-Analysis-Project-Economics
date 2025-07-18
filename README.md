# Data-Analysis-Project-Economics
# GDP Trend Analysis using Linear Regression

This project implements a linear regression model to analyze the trend of Gross Domestic Product (GDP) based on historical data and its relationship with crucial economic parameters. The analysis utilizes Python libraries such as SciKit-Learn, Pandas, Matplotlib, and Openpyxl.

## Overview

The goal of this project is to:

- Load and preprocess historical GDP data from an Excel file.
- Explore the correlation between GDP and other economic indicators (Consumption (C), Government Expenditure (G), Investment (I), and Net Exports (NX)).
- Build and train a linear regression model to predict GDP based on these indicators.
- Evaluate the performance of the model using metrics like Mean Squared Error (MSE) and R-squared.
- Visualize the actual vs. predicted GDP values.

  

## Libraries Used

- **Pandas:** For data manipulation and analysis.
- **Openpyxl:** For reading data from Excel files.
- **SciKit-Learn (sklearn):**
    - `LinearRegression`: For implementing the linear regression model.
    - `train_test_split`: For splitting the data into training and testing sets.
    - `mean_squared_error`: For evaluating the model's performance.
    - `r2_score`: For evaluating the goodness of fit of the model.
- **Matplotlib:** For data visualization.
- **Statsmodels:** For more detailed statistical analysis of the linear regression model.
- **NumPy:** For numerical operations (implicitly used by Pandas).


## Data Source

The code assumes that the GDP data and related economic parameters are stored in an Excel file (`DOC-20250324-WA0010..xlsx`). The file contained columns for GDP and the chosen economic parameters (C, G, I, NX).

## Result

**Economic Trend Analysis** 

An HTML based implementation to demonstrate the calculated equation has been provided in the repository. The code can be run on the local machine to calculate the missing economic variable (GDP, Consumption, Government Spending, Investment, or Net Exports) when the other four are known. (Solely for illustration, this HTML code is generated using online tools).
- Download the file named "Economic Trend Analysis.html" from the repository.
- Run the webpage locally to see the demo.

