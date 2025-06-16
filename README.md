# Random-Forest-Classification-Airline-
Random Forest Classification on customers for airline satisfaction 

Program: Python
Packages: Sklearn, Pandas, matplotlib, seaborn, 
source : airline_passenger_satisfaction
Objective : To identify important features that affect a passengers satisfaction when flying.


Main Fields Used: Online Boarding','On-board Service','Cleanliness','Seat Comfort','Leg Room Service','Food and Drink','In-flight Service','In-flight Wifi Service','In-flight Entertainment','Baggage Handling'
Target vaiable: Satisfaction

Key Steps

1. Null values analysed and dropped
2. Transformed coloumns containing string values to categorical values using label encoder
3. Ran a corelation matrix to identify stronger relationship that affects the satisfaction rate
4. Ran a Randomforest classifier ont the variables
5. Performed Feature importance on the variables
