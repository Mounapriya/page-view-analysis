# Page Views Analysis

This repository contains Python code to analyze daily page views data for FCC forums, retrieved from a CSV file. The code addresses data cleaning, outlier removal, and visualization using various techniques, including:

* **Box plots** to compare page view distributions before and after outlier removal.
* **Grouped bar charts** to visualize average monthly page views across years.
* **Line charts** to explore yearly trends in average page views.
* **Time series plots** to visualize daily page views over time.
* **Seasonal decomposition** to break down the time series into trend, seasonality, and residual components.
* **Rolling averages** to smooth out fluctuations and highlight underlying trends.

The code is well-structured and includes comments to explain each step of the analysis. Additionally, a Markdown document summarizes the key insights extracted from the data visualizations.

## Dependencies

This code requires the following Python libraries:

* pandas
* matplotlib.pyplot
* seaborn
* plotly.express
* statsmodels.api

## Running the Code

1. Clone this repository to your local machine.
2. Open a Python terminal or IDE and navigate to the repository directory.
3. Ensure you have the required libraries installed (`pip install <library_name>` for each library).
4. Run the Python scripts (e.g., `time_series_analysis.py`).

The code will generate various plots and a Markdown file with insights, providing a comprehensive analysis of the FCC forum page views data.

## File Description

* `time_series_analysis.py`: Main script for data cleaning, visualization, and insights generation.
* `fcc-forumpageviews.csv`: Sample CSV file containing daily page views data (replace with your actual data file).
* `README.md`: This file (you are reading it now).

## Contributing

Feel free to clone, modify, and extend this code for further analysis of your FCC forum page views data. If you make significant improvements, consider creating a pull request to contribute them back to this repository.
