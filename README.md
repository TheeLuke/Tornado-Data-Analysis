# Tornado-Data-Analysis
---
## Overview
Data analysis exploration into the effects of weather that contribute to tornadoes.

### Datasets
1. [US Tornado Dataset](https://www.kaggle.com/datasets/danbraswell/us-tornado-dataset-1950-2021?resource=download">https://www.kaggle.com/datasets/danbraswell/us-tornado-dataset-1950-2021)

Derived from a dataset produced by the National Oceanic and Atmospheric Administration (NOAA) Storm Prediction Center. This dataset contained important tornado information such as the length, width, injuries, fatalities, and magnitude. It is a CSV file that contains roughly 70,000 rows and 15 columns *(Can be found in the notebook file)*. 

The magnitude follows the **Enhanced Fujita Scale (EF)**. A tornado's destructiveness or magnitude is derived largely from the wind speed within it. Meteorologists use this Enhanced Fujita Scale since 2007 to rate tornadoes based on wind speed.

**Enhanced Fujita Scale**:
| Rate | Wind Speed | Damage |
| ----------| ---------| --------- |
| EF0 | 65-85 mph | Light damage |
| EF1 | 86-110 mph |  Moderate damage |
| EF2 | 111-135 mph | Considerable damage |
| EF3 | 136–165 mph | Severe damage |
| EF4 | 166–200 mph | Devastating damage |
| EF5 | >200 mph | Incredible damage |

2. [The Weather Dataset](https://www.kaggle.com/datasets/guillemservera/global-daily-climate-data/data?select=cities.csv)
   
Daily weather readings from major cities across the world received from central weather stations. This dataset contained valuable information regarding weather information on every single day in various states. The dataset included data such as precipitation, wind speed, temperature, and sunshine levels. It has about 30 million rows of weather data, as well as more in countries and city CSVs. The weather data is stored in a parquet file.

## Research Questions
1. Is there a correlation between annual rainfall levels and tornado frequency within states?
2. Can we predict the severity (magnitude, length, width) of tornadoes based on weather conditions?

## How to use
Instructions on how to use this repository for further analysis:

1. Download the latest release containing the Python notebook, CSVs and parquet file in a zip.
2. Extract the zip file. 
3. Open the notebook file inside the folder titled, "Tornado Machine Learning.ipynb".
