# Climate-Change-Analysis
World Bank Climate Data Analysis

Group Project:  Global Climate Analytics  














## Group Members:  	
Buddhika Sameera 
Manura Dissanayake 

# Overview 
Climate change is a change in the statistical distribution of weather patterns when that change lasts for an extended period of time. Climate change may refer to a change in average weather conditions, or in the time variation of weather within the context of longer-term average conditions. 
Powerful analytics tool is beneficial for the public to have visibility towards climate changes in order to understand the long term effect. Also this creates awareness among public to make necessary measures to minimize the impact due to human activities.   
Objective Climate data is being collected from varies sensors installed across the world and they are publicly available from different organizations including government and non-governmental institutions. By applying proper analytics on this data, it can be derived meaningful insights and predictions for the wellbeing of general public. 

# Data Sources 

The World Bank Group is one of the world’s largest sources of funding and knowledge for developing countries. Its five institutions share a commitment to reducing poverty, increasing shared prosperity, and promoting sustainable development. The data for this project is taken from open source world bank data repository. 

## Explanatory Data: World bank (Climate-Change)
https://data.worldbank.org/topic/climate-change

## Explanatory variables 

Series name  
Population  
Population growth (annual %)  
GDP ($)  
GNI per capita (Atlas $)       
Average daily min/max temperature (1961-1990, Celsius)  
Projected annual temperature change (2045-2065, Celsius)  
Average annual precipitation (1961-1990, mm)  
Projected annual precipitation change (2045-2065, mm)  
Projected change in annual hot days/warm nights  
Projected change in annual cool days/cold nights  
Land area below 5m (% of land area)  
Population below 5m (% of total)  
Population in urban agglomerations >1million (%)  
Urban population  
Urban population growth (annual %)  
Droughts, floods, extreme temps (% pop. avg. 1990-2009)  
Annual freshwater withdrawals (% of internal resources)  
Agricultural land under irrigation (% of total ag. land)  
Population living below $1.25 a day (% of total)  
Nationally terrestrial protected areas (% of total land area)  
Under-five mortality rate (per 1,000)  
Child malnutrition, underweight (% of under age 5)  
Malaria incidence rate (per 100,000 people)  
Access to improved sanitation (% of total pop.)  
Access to improved water source (% of total pop.)  
Cereal yield (kg per hectare)  
Access to electricity (% of total population)  
Paved roads (% of total roads)  
Physicians (per 1,000 people)  
Nurses and midwives (per 1,000 people)  
Foreign direct investment, net inflows (% of GDP)  
Invest. in energy w/ private participation ($)  
Invest. in telecoms w/ private participation ($)  
Invest. in transport w/ private participation ($)  
Invest. in water/sanit. w/ private participation ($)  
Disaster risk reduction progress score (1-5 scale; 5=best)  
Ease of doing business (ranking 1-183; 1=best)  
Public sector mgmt & institutions avg. (1-6 scale; 6=best)  
Primary completion rate, total (% of relevant age group)  
Ratio of girls to boys in primary & secondary school (%)  
CO2 emissions per capita (metric tons)  
CO2 emissions per units of GDP (kg/$1,000 of 2005 PPP $)  
CO2 emissions, total (KtCO2)  
GHG net emissions/removals by LUCF (MtCO2e)  
Methane (CH4) emissions, total (KtCO2e)  
Nitrous oxide (N2O) emissions, total (KtCO2e)  
Other GHG emissions, total (KtCO2e)  
Energy use per capita (kilograms of oil equivalent)  
Energy use per units of GDP (kg oil eq./$1,000 of 2005 PPP $)  
Latest UNFCCC national communication  
Annex-I emissions reduction target  
NAMA submission  
NAPA submission  
Renewable energy target  
Hosted Clean Development Mechanism (CDM) projects  
Issued Certified Emission Reductions (CERs) from CDM (thousands)  
Hosted Joint Implementation (JI) projects  
Issued Emission Reduction Units (ERUs) from JI (thousands)  

## Response Variables: World bank (climateportal)
http://sdwebx.worldbank.org/climateportal/index.cfm?page=downscaled_data_download&menu=historical.

### Temperature and precipitation are the response or dependent variables we have used for this analysis.  


# Shiny Visualization Tabs

## TAB 1: Relationship and Trend Analysis 

This provides a descriptive analysis of response variables i.e. Temperature and Precipitation as a function of explanatory variables sub setting into regions, countries. Here a user can have a data sensing of the relationship between these variables and how they are changing over period of time annually. 
A regression analysis is provided for further understanding or data taking feature matrix as explanatory variables and target variables as response variables. 

## TAB 2: Response Variable Analysis  
This provides an animation timely changing relationship between the response variables. How the maximum precipitation is changing as a function of maximum temperature in different regions globally. 

## TAB 3: Explanatory Variable Analysis 
MAP visualization to observe how the explanatory variables are distributed globally. This is provided to for the user to further have a sense of the data we use. For example, which data is not is not available, the variable distribution etc. 

## TAB 4: Reference Data 
This tab include explanation of variables. 
