# Statistical Analysis & EDA for flight fare using R
### RRProject2023

In this project, we converted and extended a Python notebook on "Statistical Analysis & EDA for flight fare" using R and Quarto notebook. The original notebook can be found on Kaggle at https://www.kaggle.com/code/ananyanandi02/statistical-analysis-eda-for-flight-fare/notebook . The dataset used for analysis contains 10,683 observations with 11 variables.

We started by loading the necessary libraries and the dataset. We performed exploratory data analysis and handled missing data. Further data cleaning involved;
- Extracted the day, month and weekday information from "Date of Journey" variable.
- Converting the "Duration" variable into minutes. 
- Categorizing the "Dep_Time" and "Arrival_Time" variables into morning, evening, night, and afternoon categories. 
- Converting the "Total_Stops" variable to numerical values.
- Converting the variables to the correct data types
- Dropping unnecessary columns to optimize the dataset, such as  "Route", "Date of Journey", "Dep_Time" and "Arrival_Time".

We explored the relationship between the variables through data visualisation. In addition, we conducted correlation analysis to examine the relationships between variables using Pearson and Kendall rank correlation tests. The correlation analysis revealed a significant and moderate positive correlation between the duration of a flight and the price of the ticket. The findings suggest that longer flights tend to have higher ticket prices. 

The regression analysis provided insights into the factors influencing flight prices and yielded models that can be used for predicting prices based on various features using simple linear regression model (lm()). The Breusch-Pagan and Jarque Bera diagnostic tests supported the assumption of homoscedasticity and normal distribution of residuals.

The regression results showed that various independent variables had significant effects on flight prices. For example, different airlines, source-destination combinations, arrival time, total stops, journey day, and weekday had significant coefficients. The overall performance of the final model was good with R-squared value of 79.5%, which indicate that the model explain a substantial portion of the variance in flight prices.

Overall, this project provided insights into the flight fare dataset and uncovered patterns and relationships that can be further analyzed and used for decision-making in the airline industry.


Technologies/Languages - Quarto Notebook, R Studio, R programming language
