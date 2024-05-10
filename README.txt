#data-cleaning-pandas


####Eduardo Da Silva, Radley Joseph, Dylan Sedeno, Maya Wilson-Fernandez, Gian F. Villafañe


## Project Overview
This project analyzes shark attack data from global sources to identify patterns and trends in shark attack incidents, with a focus on seasonal variations and the influence of Marine Protected Areas. The primary goal is to enhance understanding of when and where shark attacks are most likely to occur and to investigate the effectiveness of Marine Protected Areas in reducing these incidents.


## Problem Statement 
  Assessing the correlation between marine protected areas / shark sanctuaries and frequency of shark attacks on humans. 


## Hypotheses
- Hypothesis 1 - Shark attacks are less prevalent in Marine Protected Areas due to increased protections and more food sources.
- Hypothesis 2 - Unprovoked attacks are more prevalent in Marine Protected Areas.
- Hypothesis 3 - Shark attacks are more prevalent in warmer seasons like spring and summer. 


## Data Structuring 
### Data Cleaning and Formatting:
- Date Columns:
  - Removes prefixes like "Before" from date strings.
  - Replaces spaces with hyphens to standardize date formats.
  - Extracts month and year from the date column using regex patterns.
  - Month and Season Categorization:
  - Maps abbreviated month names to full names.
  - Applies a function to categorize months into corresponding seasons.
- Data Refinement:
  - Column Removal:
    - Drops unnecessary columns to focus the dataset on relevant data.
  - Null Value Management:
    - Drops rows with excessive null values based on a threshold to clean up the dataset.
  - Data Analysis Preparation:
    - Filtering by Country:
      - Isolates data specifically related to the USA for focused analysis.
    - Attack Type Segmentation:
      - Separates data into provoked and unprovoked attacks for detailed analysis.
    - Aggregation and Grouping:
      - Groups data by specific criteria (like country or season) to facilitate detailed analysis and understanding of patterns.
    - Output Preparation:
    - Adjusts settings to display all columns in the output, ensuring comprehensive visibility during analysis.


## Sources
- NOAA. (n.d.). The MPA Inventory. The MPA Inventory | National Marine Protected Areas Center. https://marineprotectedareas.noaa.gov/dataanalysis/mpainventory/ 
- Shark Research Institute. (n.d.). Incident Log. Retrieved from https://www.sharkattackfile.net/incidentlog.htm
