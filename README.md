# JIFS-Climate-Project
Data 422 Project | Climate Change and Population

**Overview**

This dataset was created with the aim of addressing the reasons people move around New Zealand, and whether there is a relation between the changing natural landscape and where people choose to reside.

The data consists of two separate data-frames.

The historical measurements are for earthquakes, internal migration, and weather (rainfall, temperature, and wind gusts), covering the years 2014-17 (inclusive).

The second dataset is for searise in these regions covering predictions for a range of scenarios out to 2300. The prediction to be examined can be changed via a function.

**Order of notebooks**

Initial:

- Earthquake
  - Input: 
  - Output: Earthquake_data.csv
- Migration
  - Input: 
  - Output: Migration_data.csv
- Weather
  - Input: Raw_Rain.csv, Raw_Temp.csv, Raw_Wind.csv
  - Output: Weather_data.csv
- Sea_Rise
  - Input: 
  - Output: 

Supplementery:

- NZRegions_Scraped
  - Input: Sites_df
  - Output: Sites_df_v2, Region_list

Final:

- Final_Dataset
  - Input: Earthquake_data.csv, Migration_data.csv, Weather_data.csv
  - Output: Full_data.csv, Full_data_clean.csv
- Plots
  - Input: Full_data_clean.csv
  - Output: 
