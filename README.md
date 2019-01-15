# CO2-Analysis
Aim of this analysis is to process the data to find out the highest and average CO2 level recorded in Hawaii and Alaska

# ABOUT THE FILES
There are two files, "co2_hawaii.txt" and "co2_alaska.txt". These files are been provided by the U.S. National Oceanic and Atmospheric Administration. Each file contains over 40 years of measurements of carbon dioxide levels in the atmosphere, taken from instruments at Barrow, Alaska and Mauna Loa, Hawaii.

# Processing and Analysis Steps Includes
1. Read the unmodified files and load all the data values.
2. Parse the Quality Control Flagsto know which rows have invalid data that must be ignored in calculations
3. Calculate the following items per year:

  (a) MAX_LEVEL : Highest CO2 recorded for each Country 

  (b) MEAN_LEVEL : Mean CO2 recorded for each Country 

  (c) %CHANGE : Percent Change of "Mean Level" compared to previous year




(Note: Environment used for this analysis is Jupyter Notebook)
