# Indian Railways Operational Efficiency Analysis

## Problem Statement
Indian Railways incurs significant losses due to chronic train delays, yet delay patterns remain underanalyzed at a systemic level.

## Methodology
- Data cleaning and EDA using Pandas on 1,900+ station-level delay records
- SQL queries via SQLite for extracting delay patterns
- Custom Reliability Score built per train
- Cost of delay estimation model

## Key Findings
- Only 49.78% of trains run on time
- Average delay across all stations: 40.7 minutes
- Maximum delay recorded: 586 minutes
- Top 3 bottleneck routes identified

## Tools Used
Python, Pandas, SQL, Tableau

## Live Dashboard
[View on Tableau Public](https://public.tableau.com/app/profile/riya.tuscano/viz/IndianRailwaysOperationalEfficiencyAnalysis/IndianRailwaysOperationalEfficiencyAnalysis)

## Data Limitations
- Dataset contains 1,900 station-level records scraped from public sources
- Delay figures represent averages and may not reflect real-time conditions
- Cost of delay estimates based on conservative assumptions