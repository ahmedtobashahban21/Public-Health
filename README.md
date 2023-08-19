# Air Pollution

# It is evident through this notebook the proportions of air pollutants in many places
    - Explore Phase
    - Design Phase 
    - Implement Phase

- Among these influences are: ['PM2.5', 'PM10', 'NO','NO2', 'NOX', 'CO','OZONO']

# This notebook is explanatory and presents the data we possess

# 1. Explore Phase
- First, we import libraries that we use: ( matplotlib, seaborn, ipywidget ) are mainly used.
- Implement functions::
  - create_histogram_plot: to show a histogram between stations and pollutants you can select any station and pollutant.
  - create_boxplot : to show the concentration of each pollutant in every station.
  - create_scatter_plot : to show the relation between each pollutant and the other.
  - create_plot_pair : to show pair of two pollutants.
  - create_correlation : to show the relation between pollutants, it's simply clear all the pic to your data.
  - fix_dates : Fixes the date format in the data.
  - create_time_series : measurements over time for different pollutants at different stations.


# 2. Design Phase 
steps:

- Implement Functions
- Load data
- Add Location( latitude and longitude of sensor stations ) to the data frame.
- Visualizing the extent and distribution of missing values.
- Visualizing simple methods for estimating missing values.
- Run the nearest neighbor method to establish a baseline.
**Neural Network

- prepare the data to train a neural network
- split data into training and testing sets.
- train and test neural network model to estimate missing data.
- Visualizing the result from the baseline model compared to the neural network.
- estimate missing sensor measurements across all pollutants

![Screen Recording (8-19-2023 11-32-33 PM)](https://github.com/ahmedtobashahban21/Public-Health/assets/63298272/f15a2458-1c46-41b1-8ccc-57b253e523c3)







