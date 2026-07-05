# Food-Delivery-Project
Matlab Project
Statistical Analysis of Urban Micro-Climates on Courier Dispatch 
Efficiency
Last-mile delivery in dense urban environments is extremely sensitive to micro-climate fluctuations such as 
sudden rainfall, temperature drops, and wind gusts. These environmental factors can significantly alter courier 
mobility, traffic flow, and delivery safety, ultimately increasing delivery latency.
This project investigates the statistical and machine-learning relationships between localized weather conditions 
and courier delivery performance. Using a publicly available Food Delivery Time Prediction dataset enriched 
with real historical New York City weather data. Obtained from the Open-Meteo API, the dataset contains 
Temperature, Precipitation and Wind speed, because the publicly available courier dataset did not contain 
timestamped delivery records, weather conditions were probabilistically mapped using randomized hourly 
meteorological observations. While this limits exact temporal alignment, the methodology remains statistically 
valid for exploratory urban logistics modelling and simulation based dispatch analysis.
This project investigates the statistical relationship between urban weather and dynamics and courier delivery. 
The study applies Exploratory data analysis, Multi-way ANOVA, Non-linear regression modeling, High-fidelity 
data visualization and Predictive modeling for dispatch optimization.
Initial exploratory data analysis revealed substantial variability in courier delivery durations under urban 
operational conditions. Delivery times ranged from 8 to 141 minutes across 883 valid observations indicating 
the presence of both highly efficient and severly delayed delivery scenarios. Boxplot analysis identified only 
four finite outliers, suggesting that the dataset maintained strong statistical consistency with limited anomalous 
operational behavior. These preliminary findings support the suitability of the dataset for advanced inferential 
statistical modeling and predictive logistics analysis. The delivery time distribution analysis revealed a 
strong concentration of observations with in the central operational range indicating stable baseline dispatch 
performance across the majority of observations.However, the presence of extended upper-tail distribution 
suggested occasional severe delay events consistent with urban congestion and adverse micro climate 
disruptions.Quantile - Quantile (QQ) plot was used to assess the normality assumption of delivery time 
observations prior to inferential statistical modeling.The majority of observations followed an approximately 
linear trend relative to the theoretical normal distribution, indicating acceptable overall normality with in the 
dataset.Minor devaitions observed in the lower tail region of the plot, indicating small subset of unusually short 
delivery durations. A strong positive correlation (r = 0.7832) was observed between delivery distance and 
courier delivery time, indicating that route length is the primary operational determinent of last-mile delivery 
latency.Experience vs Delivery Time has r = - 0.07679, very weak negative correlation. Which means more 
experienced couriers tend to complete deliveries slightly faster, but effect is weak.The correlation between 
precipitation and delivery duration was weakly positive( r= 0.03003), indicating limited independent linear 
influence of rainfall intensity on courier delay. The neglegible correlation between distance and windspeed 
(r = 0.00779) suggests statistical independence between environmental wind conditions and route length 
characteristics. The Anova results revealed a highly significant effect of weather conditions on courier delivery 
time ( p < 0.001). This indicates that localized urban micro climate conditions substantially influence last-mile 
delivery efficiency and operational latency. And traffic congestion strongly impacts delivery delays. Nonlinear 
regression shows rainfall alone weakly correlates, and the violin graph shows between 50 and 100 minutes their 
is high delivery time. Under the selected operational and environmental conditions, the estimated courier delay 
1
is approximately 43 minutes. Besides this, the developed Matlab Application transforms statistical findings into 
an interactive operational decision support tool for last-mile delivery amangement.
The goal is to quantify the impact of micro-climate variables on delivery cycle times and provide a robust 
predictive model that allows logistics researchers and last-mile operators to dynamically adjust dispatching 
decisions in real time.
