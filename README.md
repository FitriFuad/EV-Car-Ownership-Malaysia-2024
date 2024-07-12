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


### Data Visualization & Reporting
- Power BI: Used for generating visualizations and reports.
- GitHub: Used for publishing and recording the project.

## Data Retrieval & Cleaning Steps
### New car registration data from JPJ (Road Transport Department) data
1. Retrieve data from data.gov.my.
2. Import into Excel Power Query for cleaning.
   - Filtering electric type car only
   - Filtering unused column   

### EV stations license registration data from the ST (Energy Commission) data
1. Use webscarping function (Get Data > From Web) in Excel
2. Load html tables into Power Query for cleaning.
   - Spliting column to get states column
   - Filtering unused column  

## Data Analysis Steps
1. Import data into Power BI.
2. Establish relationships between the two data sources.
3. Create new measures using DAX (Data Analysis Expressions).
   

## Data Visualization and Reporting

![dashboard](https://github.com/FitriFuad/EV-Car-Ownership-Malaysia-2024/assets/106916338/fc6655de-7494-4fb7-ac68-90e952be73d0)
1. Creating tables and graphs to explore relationships between data.
2. Generate graphs to track trends from month to month.
3. Create graphs to examine the relationship between the availability of charging stations and car registrations across states.
4. Created slicer to filtering the data dashboard
5. [Click to download the pbix](ev-car.pbix)

   
## Findings
1. The trend of EV car registrations is increasing in Malaysia, but growth has slowed, likely due to the high prices of EVs. As of 2024, the cheapest EV available is the Neta V, priced at a base MSRP of RM 100,000. The limited availability of EVs priced below RM 100,000 is likely to pose challenges for middle-income consumers looking to purchase a new car.Source : https://www.zigwheels.my/new-cars/electric

2. In certain states, the availability of EV charging stations strongly correlate with the number of new EV car purchased. This is illustrated by the high number of new EV car registrations in the Klang Valley area, where most EV charging stations are concentrated.
   
![image](https://github.com/user-attachments/assets/4fa9f07b-6bfa-4238-930c-dcfb85dec871)

3. The increasing trend is likely influenced by government incentives. From the year 2022 to 2024 government of Malaysia has perfomed many incentive to facilitate EV industry growth this include :
     - Import and excise duty exemption for four years from January 1, 2022 to December 31, 2025.
     - Road tax exemption from 2022 - 2025
     - RM2,500 tax relief for EV charging facilities which include installation of EV chargers at home.
       Source : https://www.mof.gov.my/portal/en/news/press-citations/full-exemption-of-import-excise-duties-sales-tax-for-electric-vehicle
   


## Suggestions
1. Regulate the MSRP price of EV cars. With the upcoming new of EV Car under Malaysia brands, hopefully that will increase the number of new EV car user in Malaysia in the middle tier income.
2. Expand EV charging infrastructure: Enhancing Malaysia's EV charging network with advanced technology is crucial. This initiative will support prospective EV owners by making charging facilities more accessible nationwide.
3. Provide EV users with additional perks or incentives. The Malaysian government's present plan is doing a terrific job of encouraging people to drive electric vehicles. We may maintain the current course of action while devising a new strategy to support the expansion of the electric vehicle (EV) market and the wider use of environmentally friendly technologies.
