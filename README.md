# **Programming for Data Analysis**
***

This repository contains a Jupyter noyebook titled **'project2.ipynb'** which performs statistical anaysis on temperature readings and rainfall.

## **Overview**

The purpose of this notebook is to perform and analysis of paleo to present climate data focusing on areas such as CO2 levels, temperature anomolies and methane levesls. It will also present an analysis of Irish Rainfall and Temperature.

This notebook walks through the process of:
1. **Loading** and **cleansing** data from multiple sources
2. **Plotting** the data using appropriate charts
3. **Combining** data sets
4. **Exporting** data to multiple file types

## **Requirements**

To run the analysis in this notebook, you need to have the following Python packages installed:

- `pandas`
- `seaborn`
- `numpy`
- `json`
- `csv`
- `sklearn`

You can install these dependencies using 'pip':

```bash
pip install pandas, seaborn, numpy, json, csv, sklearn 
```

Alternatively you can install all the required dependencies from the `requirements.txt file:

```bash
pip install -r requirements.txt
```

## **Usage**

### **Steps to Run the Analysis**

1. Clone this repository:

```bash
git clone https://github.com/PeeBs68/prog_da_project2
```

2. Launch Jupyter Notebook:

```bash
jupyter notebook project2.ipynb
```

4. Open the notebook in you browser and run the cells to perform the analysis

### **Notebook Workflow**

The **project2.ipynb** notebook follows these key steps

#### 1. **Data Loading and Clensing**
    - The notebook loads in the datasets ufrom csv formats
    - Cleanses the data where appropriate

#### 2. **Data Analysis**
    - Performs analysis of the data sets
    - Combines data sets for different date ranges as required
    - Using histograms and time series plots to visualise the data 

#### 3. **Data Export**
    - Exports the fused data sets to the /exports sub folder

#### 3. **Further Analysis**
    - Discusses the results in more details
    - Predicts future trends based on past history

### **Acknowledgements**
Data Sources

CO2   
-800000 to 2001 (present is 1950) from ice cores
https://www.ncei.noaa.gov/pub/data/paleo/icecore/antarctica/antarctica2015co2composite.txt   
Taken from https://www.ncei.noaa.gov/access/paleo-search/study/17975

Link to Mauna Loa data 1959 - 2022
https://gml.noaa.gov/webdata/ccgg/trends/co2/co2_annmean_mlo.csv   
Taken from https://gml.noaa.gov/ccgg/trends/data.html   


Temperature Anomoly   
-800000 to 2000 EPICA Dome C Ice Core 
https://www.ncei.noaa.gov/pub/data/paleo/icecore/antarctica/epica_domec/edc3deuttemp2007.txt   
Taken from https://www.ncei.noaa.gov/pub/data/paleo/icecore/antarctica/epica_domec/

1850 - 2023
https://www.ncei.noaa.gov/access/monitoring/climate-at-a-glance/global/time-series/antarctic/land_ocean/12/11/1850-2023/data.csv   
Taken From https://www.ncei.noaa.gov/pub/data/paleo/icecore/antarctica/   


CH4   
-800000 to 2015
https://climatechange.chicago.gov/climate-indicators/climate-change-indicators-atmospheric-concentrations-greenhouse-gases   
Taken from https://climatechange.chicago.gov/sites/production/files/2016-08/ghg-concentrations_fig-2.csv   

1984 - 2022
https://gml.noaa.gov/webdata/ccgg/trends/ch4/ch4_annmean_gl.txt   
Taken from https://gml.noaa.gov/ccgg/trends_ch4/
