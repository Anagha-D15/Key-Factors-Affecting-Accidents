# Key-Factors-Affecting-Accidents
This project analyzes factors like traffic, fines, weather, and road conditions affecting accidents in urban and rural areas using Tableau and SAS. It uses visualizations and predictive models (Decision Tree, Regression, Neural Network, Random Forest) to find trends, compare accuracy, and suggest ways to reduce accidents.

## INTRODUCTION
Traffic accidents are one of the critical global issues that cause property damage, injury, 
and fatality. Now a days, with urbanization and the rise of car usage, especially in 
developing countries, the need to identify accidents causing factors has become the need. 
Urban areas often struggle with a lot of traffic jams because of too many vehicles, on the 
other side rural areas had bas road quality and weak enforcement on traffic rules. 
This study uses the dataset from Kaggle to find out the different factors like traffic density, 
road conditions, weather and how people drive. By using data analysis tools like tableau 
and SAS, we hope to find patterns that are not easy to see just by looking at it. By 
comparing accidents in cities and in rural areas, we can help create better plans and 
solutions to make roads safer in both places.

## PROBLEM STATEMENT: 
Despite safety initiatives, traffic accidents still happen because of many connected factors 
like weather, design and how people drive cars. The goal of this project is to look at how 
different things such as rain or traffic fines affect accidents as it is not clear what exactly 
influences the number of accidents majorly. Understanding which things really cause 
accidents can help make better safety rules, as the factors might not have the same impact 
in the cities compared to the countryside.

## DATA RESOURCE: 
Dataset: Kaggle 
<a href="https://www.kaggle.com/datasets/torresdanilo/key-factors-influencing-traffic-accidents"> Key Factors Influencing Accidents</a>

## DATASET DESCRIPTION:  
The dataset consists of 8,800 clean observations with 10 variables representing 
environmental, infrastructure, and behavioral conditions. It includes both categorical and 
numerical data points spread across rural and urban geographies across the USA region. 
• Accidents: The number of traffic accidents, including both small accidents and 
bigger ones. 
• Traffic Fine Amount: It shows the average traffic fines in the area, which tells us how 
strict rules are enforced and how actually drivers behave while driving the vehicle. 
• Traffic Density: Volume of vehicles in that particular area in range of 0 to 10, 0 being 
low and 10 being high. 
• Traffic Lights: Percentage taken of the amount of traffic lights in the area. 
• Pavement Quality: It is basically a score that rates the condition of the road, higher 
number indicates better infrastructure.  
• Urban or Rural Classification: A flag indicating yes or no, 1: Yes, 0: No. 1 as in Urban 
Area and 0 being Rural Area. 
• Average Speed: It’s the average speed of vehicles in km/h, indicating the driving 
conditions. 
• Rain Intensity: A scale from 0: Dry weather to 3: Heavy rain, it shows how much rain 
impacts the number of accidents. 
• Vehicle Count: Estimated number of vehicles that are present in that area during the 
observation. 
• Time of Day: Using a 24-hour clock ranging from 0-24 to track the accidents across 
the time of day.

## TABLEAU DASHBOARD:
  <a href="https://github.com/Anagha-D15/Key-Factors-Affecting-Accidents/blob/main/Dashboard%20Visualisation.twbx"> Tableau Dashboard</a>

  ![Tableau Dashboard 1](https://github.com/user-attachments/assets/761c74ca-8652-42be-bec6-c982b963f937)
  ![Tableau Dashboard 2](https://github.com/user-attachments/assets/a1624d5a-9675-4d98-8153-b5c998e87293)



## TABLEAU INTERPRETATION 
• Urban areas have more accidents, especially during peak hours. 
• High traffic density and poor pavement increase accident risk. 
• Rain raises accident rates. 
• Higher fines in urban areas reflect poor driver behavior. 
This concludes that accidents are driven by congestion, infrastructure, weather, and 
unsafe driving, especially in cities. 

## PREDICTIVE MODELLING 
We build 4 models using pre-processed data: 
Through predictive modelling we transformed exploration data analysis to machine 
learning modeling. Our goal was to use input variables to predict the number of traffic 
accidents, allowing proactive interventions. This phase utilizes four models: 
• Decision Tree 
• Linear Regression 
• Neural Network 
• Random Forest 
Each model is evaluated based on accuracy, interpretability, and error metrics (ASE – Average Squared Error). 

## SAS DASHBOARD:
 <a href="https://vfl-072.engage.sas.com/SASVisualAnalytics/"> SAS DASHBOARD</a>

## MODEL EVALUATION: 
• The Neural Network model achieved the lowest ASE, making it the most accurate 
model for predicting accident frequency. 
• Models like the Decision Tree and Random Forest provided interpretability and good 
generalization but did not match the precision of the Neural Network. 
• The Linear Regression model, while relatively accurate, was limited in capturing 
complex relationships among variables compared to the Neural Network. 

## RECOMMENDATIONS:
• Resurface the pavement on metropolitan highways featuring a high 
population density.  
• Construct efficient water drainage systems to mitigate the danger caused by 
rain.  
• Pay attention to chauffeurs in metropolitan areas, particularly those with lots 
of traffic violations.  
• Promote conscientious behavior through campaigns to raise awareness and 
enforced rules.  
• Embed weather-sensitive driving signals into vehicle dashboards or 
smartphone apps.  
• Use smart traffic innovations to manage density during real time. 

## LESSONS LEARNED:
1. Traffic density, fine amounts, and rain intensity were the most influential predictors 
of traffic accidents. These factors consistently showed strong correlation with 
accident rates. 
2. Accident rates were significantly higher in urban areas due to congestion, complex 
road layouts, and higher traffic violations. 
3. Among all models, the neural network achieved the highest accuracy, effectively 
capturing complex relationships in the data. 
4. The dataset had no missing values or outliers, which made preprocessing easy and 
improved model reliability. 
5. Tableau visualizations helped identify trends and supported better understanding 
and communication of key insights. 
The project highlighted how data-driven approaches can guide safer urban planning 
and policy decisions by pinpointing major accident causes and risk areas.

## CONCLUSION:
This project looks at the main factors that are affecting the number of accidents using large 
datasets and machine learning models using SAS Viya. It was found that traffic fines is the 
most influential factors when the number of accidents is considered along with the traffic 
density and weather conditions. 
After cleaning and then analyzing the data, as per ASE metrics, the Neural Network Model 
gave the most accurate results with the lowest ASE of 0.89. 
The study also found that accidents are mostly likely to happen in Urban areas and 
recommend us to work more on improving infrastructure such as pavement of roads, 
offering better driving lessons to help reduce the count of accidents. 
Future research in this area can help us to identify the accident patterns in specific areas 
![Snapshot of Neural Network of accidents May 7, 2025 at 12 40 37 PM](https://github.com/user-attachments/assets/7d32770f-1678-446e-b215-69bf0ef87f13)



