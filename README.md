# Automating Cryptocurrency API Data Pull, Processing, and Visualization

## Overview
This project automates the process of pulling cryptocurrency data (e.g., Bitcoin) from the CoinMarketCap API, saving it to a CSV file, cleaning and transforming the data, performing exploratory data analysis (EDA), and visualizing key insights.

---

## Key Features

### Automated API Data Pulling:
- Retrieves real-time cryptocurrency data using the CoinMarketCap API.
- Automatically saves the data into a CSV file (`API.csv`).

### Data Loading and Cleaning:
- Loads the data into pandas DataFrames for further processing.
- Cleans and transforms the data for readability and analysis.

### Exploratory Data Analysis (EDA):
- Analyzes the percentage changes in cryptocurrency prices over different time periods (1 hour, 24 hours, 7 days, etc.).
- Groups and calculates mean percentage changes for all cryptocurrencies.

### Visualizations:
- **Percent Changes**: A point plot visualizing percentage changes across various time frames.
- **Bitcoin Price Trends**: A time-series line plot showing Bitcoin price trends over time.

---

## Project Workflow

### API Automation:
- The `api_runner()` function automates data fetching using the CoinMarketCap API.
- Data is pulled in intervals and appended to a CSV file (`API.csv`).

### Data Cleaning and Transformation:
- The data is loaded and cleaned for inconsistencies.
- Transformed into a stacked format for better visualization and analysis.

### EDA and Visualization:
- Mean percentage changes are calculated for cryptocurrencies across multiple time frames.
- Visualizations are generated for key insights, such as:
  - Percent changes for all cryptocurrencies.
  - Bitcoin price trends over time.

---

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**:
  - `pandas`: Data manipulation and analysis.
  - `requests`: API interactions.
  - `matplotlib` and `seaborn`: Data visualization.

---

## Visualizations

### Percent Changes Across Time Frames
- Displays the percentage change in cryptocurrency prices (1h, 24h, 7d, etc.).

### Bitcoin Price Trends
- A time-series visualization of Bitcoin prices over time.

---

## File Structure
- **`API.csv`**: Stores the fetched API data.
- **`automate_crypto.py`**: The main Python script to automate the workflow.
- **Visualizations**: Automatically generated by the script.


#NOTE

### Previous Version: file attached on name `Automation_API(practice)`

This "Automated_API_Pulls" project is an improved version of my earlier work, **`Automation_API(practice)`**, which is also included in this repository. The earlier version contains:

- **Basic API Pulling**: Automated fetching of cryptocurrency data and saving it to a CSV file.
- **Data Loading and Cleaning**: Performed foundational data operations using pandas.
- **Initial Visualizations**: Basic exploratory analysis and visualizations using `matplotlib`.

### Key Improvements in the Current Version
1. **Enhanced Modularity**: Refactored into reusable functions for better code organization.
2. **Dynamic File Handling**: Used platform-independent paths for saving and loading files.
3. **Improved Error Handling**: Added handling for API and file-related exceptions.
4. **Advanced EDA**: Introduced stacked transformations and grouped percentage analysis for better insights.
5. **Improved Visualizations**: Created cleaner and more informative plots using `seaborn` and `matplotlib`.

Both versions demonstrate my journey in improving API data automation and visualization workflows.

