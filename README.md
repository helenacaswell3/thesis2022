# thesis2022
My MIT Technology and Policy Thesis: Win-Win-Win? Evaluating the Climate, Health, and Equity Benefits of Retrofitting Low Income Housing in the US.

Most of the analysis takes place in 'EERetrofitSummary.xlsx'. This is referred to as the main spreadsheet. In addition there are various folders, some of which include supporting scripts, detailed below:

1) ../Data Manipulation/LeadDataProcessing.ipynb includes scripts for taking zipped by state data files from DOE's Low-Income Energy Affordability Data Tool and querying data that is used in the analysis. The processed data is then output in LEAD_byCounty_BLD.xlsx to be pasted into the EnergyFeeder2 tab of the main spreadsheet manually.
2) ../Data Manipulation/GasStoves/GasStovebyCounty.ipynb includes scripts to combine data from ResStock and LEAD to estimate gas stove prevalence by county for use in the main spreadsheet for estimating the Asthma from Gas Stoves.
3) ../Data Manipulation/Monte Carlo Uncertainty Analysis/Monte Carlo.ipynb includes scripts for running the monte carlo uncertainty analysis. Data from the CostBenefitAnalysis tab of the mainspreadsheet is pasted into the 'MonteCarloInput.xlsx' spreadsheet to run this analysis. 
4) ../Figures/Figures.pynb includes scripts for generating county and state level heat maps among other figures from the County Data and State Data spreadsheets. The data from these spreadsheets is populated from the summary tabs of the main spreadsheet.
