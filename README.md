# US Accident Prediction
Today a lot of Accidents have been spotted due to many reasons. Most of these are weather conditions like Humidity, Temperature, Wind, Visibility, Precipitation, and so on. These reasons have made the Accidents very common these days. Using the existing dataset on the website Kaggle, we aim to :-
1. Observe the causes favouring these accidents
2. Exploratory Data Analysis of Data i.e. Visualisation of Data
3. Predict the SEVERITY of these accidents using the Best Machine Learning Model

# Modules Used
- opendatasets
- numpy
- pandas
- matplotlib
- seaborn
- calendar
- collections
- scikit-learn
- warnings
- xgboost

# Metadata
Dataset Link : https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents/US_Accidents_March23.csv
This "US_Accidents_March23.csv" Dataset contains the 7728394 records and 46 attributes
Moreover, the details of the attributes are given below :
1. ID : Specifies the Accident Identity Number
2. Source : Source from which the accident is reported (Source : 1/2/3)
3. Severity : Values ranging from 1 (Least Impact) to 4 (Highest Impact)
4. Start_Time : Start time of accident (yyyy/mm/dd hr:min:ss Format)
5. End_Time : End time of accident (yyyy/mm/dd hr:min:ss Format)
6. Start_Lat : Lattitude in GPS of Start Position
7. Start_Lng : Longitude in GPS of Start Position
8. End_Lat : Lattitude in GPS of End Position
9. End_Lng : Longitude in GPS of End Position
10. Distance(mi) : Length of road extent affected in miles
11. Description : Extra details of the accident
12. Street : Street where accident took place
13. City : City where accident took place
14. County : County where accident took place
15. State : State where accident took place
16. Zipcode : Zipcode where accident took place
17. Country : Country in US where accident took place
18. Timezone : Timezone based on Accident Location
19. Airport_Code : Unique Identity Code of Airport nearest to Accident Location
20. Weather_Timestamp : Timestamp of Weather Observation
21. Temperature(F) : Temperature in Fahrenheit
22. Wind_Chill(F) : Wind Chill in Fahrenheit
23. Humidity(%) : Humidity
24. Pressure(in) : Air Pressure in inches
25. Visibility(mi) : Visibility in miles
26. Wind_Direction : Wind direction
27. Wind_Speed(mph) : Wind Speed in miles per hour
28. Precipitation(in) : Precipitation amount in inches
29. Weather_Condition : Weather Condition (e.g. Storm, Rain, Fog, etc.) 
30. Amenity : Indicates presence of Amenity nearby
31. Bump : Indicates presence of Speed Bump or Hump nearby
32. Crossing : Indicates presence of Crossing nearby
33. Give_Way : Indicates presence of Give-Way nearby
34. Junction : Indicates presence of Junction nearby
35. No_Exit : Indicates presence of No-Exit nearby
36. Railway : Indicates presence of Railway nearby
37. Roundabout : Indicates presence of Roundabout nearby
38. Station : Indicates presence of Station nearby
39. Stop : Indicates presence of Stop nearby
40. Traffic_Calming : Indicates presence of Traffic-Calming nearby
41. Traffic_Signal : Indicates presence of Traffic-Signal nearby
42. Turning_Loop : Indicates presence of Turning-Loop nearby
43. Sunrise_Sunset : Indicates period of day (day/night) based on Sunrise or Sunset when accident took place
44. Civil_Twilight : Indicates period of day (day/night) based on Civil Twilight when accident took place 
45. Nautical_Twilight : Indicates period of day (day/night) based on Nautical Twilight when accident took place
46. Astronomical_Twilight : Indicates period of day (day/night) based on Astronomical Twilight when accident took place

# Machine Learning Models Used
1. Decision Tree Classifier
2. XG Boost Classifier (XGB)
3. K Neighbors Classifier (KNN)
4. Random Forest Classifier
5. Support Vector Classifier (SVC)
6. Gaussian Naive Bayes
7. Logistic Regression
