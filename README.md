# AirlineDataAnalysis

## Live Demo
Explore the results of our analysis on our [Live Server](https://adamkaniasty.github.io/AirlineDataAnalysis/). :globe_with_meridians:

## Overview
The **AirlineDataAnalysis** project investigates passenger flight delays in the USA from 1987 to 2008. The goal is to answer pertinent questions that are of interest to both passengers and airline carriers, using a comprehensive dataset and advanced data analysis techniques.

## Data Sources
The main dataset used in this project is available from the [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/HG7NV7), containing detailed information about commercial flights. Additional data sources were also utilized, and the corresponding CSV files can be found in the `data/` folder of this repository.

## Project Goals
- Formulate interesting questions regarding passenger flight delays. :airplane:
- Explore and analyze the available data. :gear:
- Visualize the results to generate valuable insights for passengers and carriers. :bar_chart:

## Questions Addressed

### Passenger Perspective
1. What weather conditions influence weather-related delays?
2. Which airports should be avoided for connections due to cascade delays?
3. What does a map of the USA reflecting the size of delays look like?

### Carrier Perspective
1. Which carrier recorded the most safety-related delays?
2. Is there a correlation between the average delay of a carrier's planes and its customer ratings?
3. Which planes in the fleets of different airlines generated the least delays? Does the reliability of a plane depend on factors such as the year of production and the manufacturer?

## Technologies Used
- **Database**: MySQL for storing the large dataset (~12GB).
- **Data Analysis & Visualization**: 
  - **R**: For data transformation, analysis, and visualization.
  - **Packages**: 
    - `RMySQL`: For executing SQL queries from R.
    - `ggplot2`, `plotly`, `gganimate`, `ggthemes`: For creating interactive and static visualizations.
    - `lubridate`, `dplyr`: For data manipulation and transformation.

## Methodology
1. **Data Storage**: The flight data was stored in a MySQL database due to its large size.
2. **Data Retrieval**: SQL queries were executed using the `RMySQL` package to retrieve relevant information.
3. **Data Analysis**: Data was analyzed and visualized in R using various packages.
4. **Presentation**: The final analysis was compiled into an `.rmd` file and converted to an interactive `.html` document for presentation.

## Authors
- Adam Kaniasty
- Hubert Kowalski
