# Sri Lanka Tourism Dashboard

My first Power BI dashboard, exploring tourist arrivals from eight international markets and Sri Lanka’s national tourism earnings during 2021–2025.

## Project Purpose

Support a Sri Lankan hotel group in exploring source-market priorities for December–April marketing.

## Tools Used

- Microsoft Power BI Desktop
- Power Query
- DAX
- Microsoft Excel

## Dashboard Features

- Interactive year filtering
- Summary cards for arrivals and national earnings
- December–April arrivals by country
- Monthly arrival comparisons
- Annual arrival shares
- National tourism earnings over time
- Country drill-through and page navigation
- Annual validation table

## Selected Markets

Australia, China, France, Germany, India, Russian Federation, United Kingdom and United States.

## Data Model

Two fact tables—Tourist Arrivals and Tourism Earnings—connect to date and country dimensions where applicable.

Country filters apply to arrivals. Tourism earnings are national totals and have no country relationship.

## Screenshots

### Tourism Overview
![Tourism Overview](<sri-lanka-tourism-dashboard/Screenshot 2026-11-25 124450.png>)

### Country Detail
![Country Detail](<sri-lanka-tourism-dashboard/Screenshot 2026-11-25 130100.png>)

### Data Model
![Data Model](<sri-lanka-tourism-dashboard/Screenshot 2026-11-25 124527.png>)

## Data Sources

- [Sri Lanka Tourism Development Authority](https://www.sltda.gov.lk)
- [Central Bank of Sri Lanka — External Sector Tables](https://www.cbsl.gov.lk/en/statistics/statistical-tables/external-sector)

Source data remains subject to the publishers’ applicable terms.

## Validation and Limitations

Annual totals and selected monthly values were compared with the original source files.

- National arrivals do not directly measure bookings or profitability for an individual hotel.
- National tourism earnings cannot be attributed to individual source countries.
- December–April totals combine selected months across calendar years rather than one continuous season.
- Monthly comparisons aggregate the selected years; they are not monthly averages.

## Learning and Assistance

This project helped me practise data transformation, modelling, DAX, validation and interactive reporting.

ChatGPT assisted with technical guidance, troubleshooting, presentation suggestions and documentation wording.
