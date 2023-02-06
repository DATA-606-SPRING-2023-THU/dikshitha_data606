# Vehicle Crashes Prediction in Maryland State

## Datasets:
1. Vehicle crashes Data - https://opendata.maryland.gov/Public-Safety/Maryland-Statewide-Vehicle-Crashes/65du-s3qu
2. Person Details - https://opendata.maryland.gov/Public-Safety/Maryland-Statewide-Vehicle-Crashes-Person-Details-/py4c-dicf

Dataset size: ~1 GB

Number of Columns: 55 in Dataset 1, 48 in Dataset 2
Number of Rows: 849K in Dataset 1, 1.9M in Dataset 2


**Column Names and their Type:**

YEAR	Number
QUARTER	Plain Text
LIGHT_DESC	Plain Text
LIGHT_CODE	Number
COUNTY_DESC	Plain Text
COUNTY_NO	Number
MUNI_DESC	Plain Text
MUNI_CODE	Number
JUNCTION_DESC	Plain Text
JUNCTION_CODE	Number
COLLISION_TYPE_DESC	Plain Text
COLLISION_TYPE_CODE	Number
SURF_COND_DESC	Plain Text
SURF_COND_CODE	Number
LANE_CODE	Number
RD_COND_DESC	Plain Text
RD_COND_CODE	Number
RD_DIV_DESC	Plain Text
RD_DIV_CODE	Number
FIX_OBJ_DESC	Plain Text
FIX_OBJ_CODE	Number
REPORT_NO	Plain Text
REPORT_TYPE	Plain Text
WEATHER_DESC	Plain Text
WEATHER_CODE	Number
ACC_DATE	Plain Text
ACC_TIME	Plain Text
LOC_CODE	Plain Text
SIGNAL_FLAG_DESC	Plain Text
SIGNAL_FLAG	Plain Text
C_M_ZONE_FLAG	Plain Text
AGENCY_CODE	Plain Text
AREA_CODE	Plain Text
HARM_EVENT_DESC1	Plain Text
HARM_EVENT_CODE1	Number
HARM_EVENT_DESC2	Plain Text
HARM_EVENT_CODE2	Number
RTE_NO	Number
ROUTE_TYPE_CODE	Plain Text
RTE_SUFFIX	Plain Text
LOG_MILE	Number
LOGMILE_DIR_FLAG_DESC	Plain Text
LOGMILE_DIR_FLAG	Plain Text
MAINROAD_NAME	Plain Text
DISTANCE	Number
FEET_MILES_FLAG_DESC	Plain Text
FEET_MILES_FLAG	Plain Text
DISTANCE_DIR_FLAG	Plain Text
REFERENCE_NO	Number
REFERENCE_TYPE_CODE	Plain Text
REFERENCE_SUFFIX	Plain Text
REFERENCE_ROAD_NAME	Plain Text
LATITUDE	Number
LONGITUDE	Number
LOCATION	Point

- This data is Geographical which covers all the county's of Maryland State.
- It is Time Series Data which covers data for Maryland from January 2015 through September 2022.
- The label I want to predict is "Vechile Crash". The Features I wish to use are Surface Condition, Location, Weather conditions, and Collision type.
-  The ML models I plan to use are Logistic Regression, Decision Tree, and Random Forest.
-   
- 


#### _1. What is your issue of interest?_
 
My issue of interest is to detect Vehicle Crash using different surface and weather conditions related aspects of a state. According to the National Safety Council report, approximately 38,300 people were killed and about 4.4 million injured in the road accidents United States in 2015. There are a variety of reasons that contribute to accidents. Some of the reasons are adverse Weather and Traffic conditions that cause accident prone situations. Predicting likelihood of vehicular crashes due to the effect of Weather and Traffic features would be a major step towards achieving better road safety.

### _2. Why is this issue important to you and/or to others?_

In order to lessen the negative effects of crashes, timely information must be sent to traffic management centers and the general public. For the purpose of protecting highway traffic and preventing secondary crashes, crash risk prediction is essential.

#### _3. What questions do you have in mind and would like to answer?_

- What kind of models can be used?
- What measure can I use to compare the models?
- How can I handle data with more dimensionality?

#### _4. Where do you get the data to analyze and help answer your questions_
## Datasets:
1. Vehicle crashes Data - https://opendata.maryland.gov/Public-Safety/Maryland-Statewide-Vehicle-Crashes/65du-s3qu
2. Person Details - https://opendata.maryland.gov/Public-Safety/Maryland-Statewide-Vehicle-Crashes-Person-Details-/py4c-dicf

Dataset size: ~1 GB

Number of Columns: 55 in Dataset 1, 48 in Dataset 2
Number of Rows: 849K in Dataset 1, 1.9M in Dataset 2

#### _5. What will be your unit of analysis_
The unit of analysis is a Vehicle Crash.

#### _6.What variables/measures do you plan to use in your analysis_

The Features I wish to use are Surface Condition, Location, Weather conditions, and Collision type.


#### _7.What kinds of techniques/models do you plan to use_
I will be using dimensionality reduction techniques as the number of columns are more and rows a are less
I will use classification techniques like:
- Logistic regression
- Decision tree 
- SVM

 I will compare each algorithm and select the best one and the evaluation metrics would be accuracy. I am also planning to predict the best model using Confusion Matrix.
 
 
 #### _8.How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?_
My plan of action is to analyze the data first, research various types of ML models and come up with the best suited ones and implement a solution for the selected problem.


#### _9.What outcomes do you intend to achieve_
- I intend to observe and learn how ML model creation process looks, how to research various models, create them and select the best one out of them.
- To perform and achieve Exploratory Data Analysis(EDA).

