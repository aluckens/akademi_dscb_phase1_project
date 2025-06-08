![Aviation market](./Images/Aviation-Market.jpg "Aviation market")
# Risk Evaluation for Aviation Division Expansion
## Overview
This analysis evaluates aviation accident data to identify the lowest-risk airplanes for commercial and private enterprises to provide actionable insights for the company's new aviation division to guide aircraft purchasing decisions.


## Business Understanding
The company is entering the aviation industry, will be focusing on operating airplanes for commercial and private enterprises. As a new player, it aims to minimize risks—safety (accidents/fatalities). This analysis will leverage historical accident data to identify the safest airplanes for these uses. Insights will guide the head of the new aviation division in making secure, cost-effective aircraft purchasing decisions.


## Data Understanding
The dataset contains aviation accident records, which will be used to identify airplanes with the lowest safety risks, the following steps explore the dataset’s structure, content, and quality to understand its potential for risk analysis.


## Data Preparation
This section cleans and preprocesses the aviation accident dataset to ensure data quality for analyzing low-risk airplanes and comparing them to another aircraft type. Steps include handling missing values, standardizing text, filtering for relevant aircraft categories, and creating derived columns for risk analysis.


## Analysis and Results/Recommendations
The analysis focused on identifying low-risk airplanes and comparing them to helicopters. A risk score will be calculated for each aircraft type based on injury rate, fatality rate, and damage severity.

![injury_rates_risk_scores_Airplane](./Images/injury_rates_risk_scores_Airplane.png "injury_rates_risk_scores_Airplane")
![injury_rates_risk_scores_Helicopter](./Images/injury_rates_risk_scores_Helicopter.png "injury_rates_risk_scores_Helicopter")
The charts above show the injury rates (bars) and risk scores (line) for the top 30 low-risk airplanes and helicopters. The Airplane Boeing 737, Cessna aircraft company 172Rg and the helicopter Robinson R22 Beta and Schweizer 269C consistently show low injury rates and risk scores, making them ideal candidates.

## Business Recommendations
Based on the analysis, the following recommendations are provided to the head of the new aviation division:

### Business Recommendation 1: Prioritize Boeing 737 for Airplane Operations
The Boeing 737 has the lowest injury rate (0.126193) and risk score (0.199628) among airplanes, reflecting a strong safety record for commercial use.
Purchase 2–3 newer models Boeing 737 or Airplane Cessna Aircraft Company 172Rg with updated safety systems, invest in extensive pilot and maintenance training, and begin with a small fleet for controlled operations.

### Business Recommendation 2: Select Robinson R22 Beta for Helicopter Operations
The Robinson R22 Beta has the lowest injury rate (0.219780) and risk score (0.241442) among helicopters, suitable for training or light commercial roles like sightseeing.
Acquire R22 Betas, provide specialized pilot and maintenance training due to higher complexity, and limit initial use to low-risk environments.


## Conlusion and Next Steps
This analysis has enabled data-driven insights into aircraft safety profiles. Aircraft such as the Boeing 737 demonstrate high operational safety with many incidents resulting in no or minor injuries.

1. Procure newer 737s and R22 Betas from reliable suppliers.
2. Develop comprehensive training for pilots and crews.
3. Analyze demand for commercial routes (737) and niche services (R22 Beta).
4. Implement a safety tracking system for ongoing risk assessment.


## Repo Structure
```
akademi_dscb_phase1_project/
│
├── Data/
│   ├── AviationData.csv
├── Images/
│   ├── Aviation-Market.jpg
│   ├── injury_rates_risk_scores_Airplane.png
│   ├── injury_rates_risk_scores_Helicopter.png
├── .gitignore
├── index.ipynb
├── index.ipynb.pdf
├── LICENSE
├── README.md
├── presentation.pdf
```