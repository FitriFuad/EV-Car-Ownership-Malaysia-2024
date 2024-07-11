# EV Car Ownership in Malaysia for 2024

## Project Overview 
This project aims to study the ownership of EV cars among Malaysians for the year 2024.

## Data Sources
- New car registration data from JPJ (Road Transport Department)
  - https://data.gov.my/data-catalogue/registration_transactions_car
- EV stations license registration data from the ST (Energy Commission) website
  - https://www.st.gov.my/web/general/details/966
   
## Research Questions
1. Is there an increasing trend in EV car ownership?
2. What external factors are affecting new EV purchases?
3. Does the availability of EV charger stations in certain states affect the number of new purchases?

## Limitations
- Data is only available for the period from January 2024 to June 2024.
- Issues with data accuracy from Rakan Niaga in state registrations.
  - In the raw data 'Rakan Niaga'; this either indicates the state of the JPJ office the car was registered at, or that the car was registered through an official JPJ partner portal ('Rakan Niaga').
  - The 'Rakan Niaga' was filtered when do analysis for the number of car registered by states.

## Tools Used
### Data Cleaning & Data Scraping
- Excel: Used for cleaning unused data.
  
### Data Analysis
- Power BI: Used for data analysis and data model relationship.
- Powe BI : Also used to set new DAX measure to be use in the reports.

### Data Visualization & Reporting
- Power BI: Used for generating visualizations and reports.
- GitHub: Used for publishing and recording the project.

## Data Retrieval & Cleaning Steps
### JPJ Data
1. Retrieve data from data.gov.my.
2. Import into Excel Power Query for cleaning.

### ST Data
1. Use `getData` functions with the web.
2. Copy tables into Power Query.
3. Clean the data.

## Data Analysis
1. Import data into Power BI.
2. Establish relationships between the two data sources.
3. Create new measures using DAX (Data Analysis Expressions).

## Data Visualization and Reporting

![dashboard](https://github.com/FitriFuad/EV-Car-Ownership-Malaysia-2024/assets/106916338/fc6655de-7494-4fb7-ac68-90e952be73d0)
1. Create tables and graphs to explore relationships between data.
2. Generate graphs to track trends from month to month.
3. Create graphs to examine the relationship between the availability of charging stations and car registrations across states.

   


## Findings
1. There is an increasing trend in EV car registrations in Malaysia but the number quite stagnant this probably the prices of EV car 
2. In certain states, there is a little correlation between the quantity of EV charging stations available and the number of EV car registrations.
3. The increasing trend is likely influenced by government incentives.
   - From the year 2022 to 2024 government of Malaysia has perfomed many incentive to facilitate EV industry growth this include :
     - 
   


## Suggestions
1. Increase the number of EV charging stations.
2. Regulate the MSRP price of EV cars.
3. Introduce new incentives or benefits for EV users.
