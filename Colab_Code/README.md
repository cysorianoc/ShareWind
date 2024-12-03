# ShareWind Colab Code Repository

This repository contains code and resources for analyzing and visualizing data related to offshore wind turbines, specifically focusing on shared anchor concepts for floating offshore wind turbines (FOWTs). The code is designed to run in Google Colab, making it accessible and easy to use for researchers and practitioners in the field.

## Repository Structure

The repository is organized as follows:

- **Colab_Code/**: Contains Jupyter notebooks and Python scripts for data analysis and visualization.
  - `ShareWind_Analysis.ipynb`: Main Jupyter notebook for performing analysis on shared anchor concepts for FOWTs.
  - `utils.py`: Utility functions used in the analysis.
  - `data/`: Directory containing sample data files used in the analysis.
    - `df_load_0deg.csv`: Dataframe for 0-degree wind-wave-current (WWC) direction.
    - `df_load_30deg.csv`: Dataframe for 30-degree WWC direction.
    - `df_load_60deg.csv`: Dataframe for 60-degree WWC direction.

## Code Explanation

### Multidirectional_Loads.ipynb

This Jupyter notebook provides a comprehensive analysis of shared anchor concepts for FOWTs. The notebook includes the following sections:

1. **Data Loading**: Loads the data from the `data/` directory into pandas DataFrames.
2. **Data Preprocessing**: Cleans and preprocesses the data for analysis.
3. **Resultant Force Analysis**:
   - Plots the resultant force orientation for different WWC directions (0, 30, and 60 degrees).
   - Generates histograms of the resultant force angles.
   - Creates windrose plots and polar plots to visualize the distribution of resultant force angles.

### utils.py

This Python script contains utility functions used in the analysis, such as:

- **load_data(file_path)**: Function to load data from a CSV file into a pandas DataFrame.
- **plot_resultant_force(df, title)**: Function to plot the resultant force orientation for a given DataFrame.
- **plot_histogram(df, title)**: Function to plot the histogram of resultant force angles for a given DataFrame.
- **plot_windrose(df, title)**: Function to plot the windrose for a given DataFrame.


## How to Use

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/cysorianoc/ShareWind.git
   cd ShareWind/Colab_Code
