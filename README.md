# EV Car Ownership in Malaysia for 2024

## Project Overview 
This project aims to study the ownership of EV cars among Malaysians for the year 2024.

## Data Sources
- New car registration data from JPJ (Road Transport Department)
- EV stations license registration data from the ST (Energy Commission) website

## Research Questions
1. Is there an increasing trend in EV car ownership?
2. What external factors are affecting new EV purchases?
3. Does the availability of EV charger stations in certain states affect the number of new purchases?

## Limitations
- Data is only available for the period from January 2024 to June 2024.
- Issues with data accuracy from Rakan Niaga in state registrations.

## Tools Used
### Data Cleaning & Data Scraping
- Excel: Used for cleaning unused data.
  
### Data Analysis
- Power BI: Used for data analysis.

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
1. Create tables and graphs to explore relationships between data.
2. Generate graphs to track trends from month to month.
3. Create graphs to examine the relationship between the availability of charging stations and car registrations across states.

## Findings
1. There is an increasing trend in EV car registrations in Malaysia.
2. A subtle relationship exists between the number of available EV charging stations and the number of car registrations in some states.
3. The increasing trend is likely influenced by government incentives (further study needed).

## Suggestions
1. Increase the number of EV charging stations.
2. Regulate the MSRP price of EV cars.
3. Introduce new incentives or benefits for EV users.