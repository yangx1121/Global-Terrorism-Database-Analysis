# Global-Terrorism-Database-Analysis

## Project Description:
* Competition: Data2Lab Hackathon
* Organizer: GWU Chapter of American Statistical Association
* Time: Apr. 2018
* Group Member: Xuan Yang, Lauren, Terrance, Jui-Ying 
* Instructor: Mikhail Flom, Data Scientist at IBM(linkedin.com/in/mrflom)
* Award: The Best Visualization Prize, in recognition of outstanding visual representation of data

## Procedure:
* Explored for global terrorism attack dataset; 
* Conducted descriptive analysis of most common & most deadly attack methods; 
* Visualized geographical distribution of terrorist group and target regions by Tableau; 
* Built a logistic regression model to predict “Success Attack” based on R; 
* Tested by confusion matrix for Validation and Test dataset, and values of sensitivity are almost around 95%.

## Challenges: 
The most challenging data analysis project I confronted with was the Analysis of Global Terrorism Database when I attended the Hackathon Competition organized by GWU and GMU chapters of the American Statistical Association. There were a couple of aspects I would like to share to indicate its challenging and show my efforts to contributions:

1)The first challenging thing was the big size of database and numerous attributes of datasets. The database contains worldwide terrorist attacks that occurred from January 1st 1970 through December 31 2016. It has 170351 observations and each observation has 108 attributes standing for more than 170 thousand terrorist attacks around the world and its characteristics.

2)The time was limited. The competition started from 9:30 and asked participants to submit code as well as powerpoint at 3:45pm. So I need to quickly understand the meanings of each term and data type, and recognize the most interesting problem we need to describe or predict by exploring this dataset. Besides, it had high demand of cooperating with teammates and all work should be done within group collaboration. Fortunately, my other three teammates are also good at several technical skills such as R, SQL and Tableau. And we quickly decided on our storyline: Does the success of an attack depend on the type of attack?

3)There were lots of problems emerging when we cleaned the dataset. Many of data types were wrongly classified; there were huge amount of missing values and lots of data contents were not structured, etc. We subset the dataset by choosing attacks occurred only after 2013 and selected columns only related to success of attacks as well as types of attacks. After that, we at first transformed all data types if they needed, and normalized all related numeric data, also replaced NULL with blank in all categorical data, then imputed all missing values. Our main softwares processing dataset were R and SAS JMP pro.

4)In data analytics period, we separated our storyline into two parts. The first part is the geographic distribution and corresponding active terrorist groups of most common & most deadly attack methods. We used Tableau and make use of the geographic coordinate system to elaborate frequency of attack weapon types through clusters on a world map in Tableau. We took advantages of color, shape and circle size to distinguish different most common and deadliest attacks within certain regions, which had the highest density of attacks. We found that the most common & deadliest attacks were armed assault, bombing and hostage taking within Iraq, Nigeria, Afghanistan and Kenya. Also, we wanted to see if specific groups were operating in these areas, and found that AI-Shabaab, Boko Haram, Islamic State and Taliban were the top 4 most active terrorist groups who were executing independently in the four areas with the most attacks. Besides, we used 3 dimensional histogram to describe which group favored which tactics. We found that all groups used a mixture of all attacks but hostage taking resulted in the highest deaths.

5)We also conducted predictive analysis by creating a logistic regression model to predict for the probability of success in the future attack on SAS JMP Pro. At first, we partitioned selected dataset into training, validation and test dataset by 50%, 25%, 25% respectively. Then, we set binary variable "success" as target variable and selected 17 variables mixing numeric and categorical as predictors. Then we sorted predictors by LogWorth, namely contribution percentage and deleted all predictors whose P-value was less than 0.05. Also, we got parameter estimates which indicated positive or negative relationship. When we ran confusion matrix of validation dataset, we got a satisfiable result which has 97.41% of sensitivity. As a conclusion, we assumed that the success of an attack does not only depend on the type of attack, but also on other important factors, like whether or not the property is damaged, types of weapon, etc.

Through this Hackathon competition, I learned a lot for improving my analytics skills from my teammates and was honored to be award as Best Visualization amongst all of teams. Attached files contain our visualization output of data analysis, and honor certificate of this Hackathon.

