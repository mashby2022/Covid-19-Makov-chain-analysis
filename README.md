# COVID-19 Data Analysis Project

## Project Overview
In this  project, I showcase my expertise in statistics and data analysis, particularly focusing on COVID-19 data. The project's primary objective was to analyze the waves of COVID-19 cases, measuring their intensity and duration. 

<img width="500" alt="Screen Shot 2024-01-07 at 5 37 25 PM" src="https://github.com/mashby2022/Covid-19-Makov-chain-analysis/assets/100232008/46aa3f31-708c-48d6-92dc-0728fd863251">

## Tools and Skills 

### 1. Excel
- **Proficiency:** Excel was the primary tool used for data manipulation, calculations, and visualizations throughout the project.
- **Data Processing:** I leveraged Excel to process and analyze the COVID-19 data effectively.

### 2. Statistics
- **Statistical Models:** I applied discrete-time Markov chain models to mimic the patterns observed during the COVID-19 pandemic.
- **Probability Calculations:** Probability calculations were essential for determining transition probabilities and expected lengths of COVID-19 case inflation and decline periods.

### 3. Data Extrapolation
- **Data Sources:** Real-world COVID-19 data from the CDC was utilized as the basis for transition probabilities.
- **Data Extrapolation:** I extrapolated weekly transition probabilities to create a week-by-week transition structure for our model.


## Key Findings and Processes

### Assumptions
- Transition probabilities for each state were assumed, with a focus on four separate states: 10% and 50% increases in diagnosis rates and 10% and 50% reductions in diagnosis rates.
- Acceptable ranges for transition probabilities were established to improve the realism of the model.

### Geometric Probability Model
- To determine the expected lengths of periods of case inflation and decline, a geometric probability model was employed.
- Expected values for the lengths of increase and decrease periods were calculated using transition probabilities.

### Most Occurring State
- I applied an Excel-based method to calculate the most occurring state in our model.
- The steady-state vector for each state was calculated, and it was determined that the most occurring state was a 50% increase in COVID cases.

## Conclusion and Insights
My analysis revealed that the most frequently occurring state during the COVID-19 pandemic was a 50% increase in cases. This finding corresponds to the numerous surges and closures experienced across California during the pandemic.

Overall, the project successfully developed a Markov chain model to simulate COVID-19 case patterns. I demonstrated my ability to make assumptions using real-world data, calculate transition probabilities, and determine the most occurring state. Our model aligned with actual data trends, making it a reliable tool for understanding the dynamics of COVID-19 case fluctuations.

While the project achieved its goals, I encountered challenges, such as determining the most occurring state and refining transition probability ranges. Further refinement and validation could enhance the accuracy of the model. Additionally, a more standardized process for extrapolating data rates may streamline future analyses.

References:
- [CDC COVID Data Tracker](https://COVID.cdc.gov/COVID-data-tracker/#trends_totalandratecasessevendayrate)
- [Our World in Data - Weekly Growth COVID Cases](https://ourworldindata.org/grapher/weekly-growth-covid-cases?stackMode=absolute&time=2020-05-23&country=~USA&region=World)
- [SFGate - Coronavirus COVID-19 Fourth Wave Surge](https://www.sfgate.com/bayarea/article/coronavirus-COVID-California-fourth-wave-surge-15961728.php)
