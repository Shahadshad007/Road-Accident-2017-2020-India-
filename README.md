# Road-Accident_2017-2020-India 

## Overview  
This repository contains the Power BI dashboard and associated datasets for analyzing road accidents in India. The dashboard provides a comprehensive view of road accident statistics across Indian states and union territories (UTs) for the years 2017 to 2020.  

## Features  
- **Interactive Dashboard**: Analyze data trends, rankings, and year-over-year changes in road accident statistics.  
- **Key Insights**:  
  - Fatal accidents and total accidents.  
  - Number of  injuries and deaths.  
  - Rankings of states/UTs based on accidents .  
  - Accidents on different highways.  

## Datasets  
The repository includes the following datasets:  

1. **Road Accidents and Fatalities Dataset**:  
   - **Columns**:  
     - `State/UT`: Name of the state or union territory.  
     - `Fatal Accidents (2017-2020)`: Number of fatal accidents for each year.  
     - `Accidents (2017-2020)`: Total number of accidents for each year.  
     - `Rank (2020)`: Rank of states/UTs in 2020 based on accident data.  
     - `Killed (2017-2020)`: Number of fatalities for each year.  
     - `Injured (2017-2020)`: Number of injuries for each year.  
   

2. **State Highways Dataset**:  
   - **Columns**:  
     - `States/UTs`: Name of the state or union territory.  
     - `Total Number of Road Accidents on State Highways (2017-2020)`: Data segmented by year.  
     - `Rank (2020)`: Rank of states/UTs in 2020 based on highway accidents.  
   - **Source**: Data specific to state highway accidents.  
3. **National Highways Dataset**:  
   - **Columns**:  
     - `States/UTs`: Name of the state or union territory.  
     - `Total Number of Road Accidents on National Highways (2017-2020)`: Data segmented by year.  
     - `Rank (2020)`: Rank of states/UTs in 2020 based on highway accidents.
2. **Other Roads Dataset**:  
   - **Columns**:  
     - `States/UTs`: Name of the state or union territory.  
     - `Total Number of Road Accidents on Roads (2017-2020)`: Data segmented by year.  
     - `Rank (2020)`: Rank of states/UTs in 2020 based on highway accidents.  
 
## Dashboard Highlights  
The Power BI dashboard provides the following:  
- **Interactive Filters**: Allows users to filter data by year, state/UT, or accident type.  
- **Visualization Types**:  
  - Bar charts for year-wise comparisons.  
  - Heatmaps for ranking states/UTs based on accident severity.  
  - Line charts for trends over time.  
- **Insights and Key Metrics**: Summarized statistics for accidents, fatalities, and injuries.  

## Repository Structure

- **Dashboard**
  - `Road Accident 2017-2020 (India).pbix` - Power BI file with the interactive dashboard.
  
- **Dataset**
  - `Road AccidentsKilled_On_National_Highway_2017_2020.xlsx` - Data on fatalities on national highways.
  - `Road Accidents_2017_2020.xlsx` - General road accidents data for 2017-2020.
  - `Road Accidents_Fatal_2017_2020.xlsx` - Fatal road accidents data for 2017-2020.
  - `Road Accidents_Fatal_On_National_Highway_2017_2020.xlsx` - Fatalities on national highways.
  - `Road Accidents_Fatal_On_State_Highways_2017_2020.xlsx` - Fatalities on state highways.
  - `Road Accidents_Injured_2017_2020.xlsx` - Injuries resulting from road accidents for 2017-2020.
  - `Road Accidents_Injured_On_National_Highway_2017_2020.xlsx` - Injuries on national highways.
  - `Road Accidents_Injured_On_State_Highways_2017_2020.xlsx` - Injuries on state highways.
  - `Road Accidents_Killed_2017_2020.xlsx` - Killed individuals in road accidents for 2017-2020.
  - `Road Accidents_Killed_On_State_Highways_2017_2020.xlsx` - Killed individuals on state highways.
  - `Road Accidents_On_National_Highway_2017_202.xlsx` - Data for road accidents on national highways.
  - `Road Accidents_On_Other_Road_2017_2020.xlsx` - Data for road accidents on other roads.
  - `Road Accidents_On_State_Highway_2017_2020.xlsx` - Data for road accidents on state highways.


## Overview

This dashboard provides an interactive overview of road accidents in India over the years 2017-2020, categorized by the following:
- **Fatalities**: Number of people killed in road accidents.
- **Injuries**: Number of people injured in road accidents.
- **Accidents**: Total number of accidents reported.

The data is split by different categories:
- **National Highways**
- **State Highways**
- **Other Roads**

## How to Use

1. **Clone the Repository**
   - Clone this repository to your local machine.
     

2. **Open the Power BI Dashboard**
   - Open the `.pbix` file using Power BI Desktop.
   - Navigate to `Road Accident 2017-2020 (India).pbix` and explore the dashboard.

3. **View the Data**
   - The Excel files are provided in the `Dataset` folder.
   - Open the relevant Excel file to explore the dataset used for the dashboard.

## Dependencies

- **Power BI Desktop**: To view and interact with the `.pbix` Power BI dashboard file.
- **Microsoft Excel**: To view and interact with the dataset files in `.xlsx` format.


## Acknowledgments

- This dashboard was built using publicly available data on road accidents in India for the years 2017-2020.
- Special thanks to the contributors and sources of the road accidents data.
