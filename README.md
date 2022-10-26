## Airfare prediction for dometic Indian flights 2019

###### This work is part of the Udemy course "Data Science Real World Projects in Python". All the datasets used for the projects are from the course.

The project is aimed at airfare predictions. It is carried out in several steps as mentioned below.
1.  AirFare_Dataset_preparation.ipynb - Data type verification, deriving new features based on the deparature and arrival time variables.
2. Airline_EDA.ipynb - A comprehensive EDA task is carried out on the dataset and below insights were found.
    - The highest number of flight departures are reported in the morning between 05:00-12:00 whereas the least is reported at night from 21:00-05:00.
    - Jet Airways has the highest percentahe of flight operaions which add up to 36%.
    - There are five source-destination pairs exists in the dataset. Out of that the highest percentage of flights are operated between Delhi and Cochin (42%). 
    - Air India, Vistara, SpiceJet, and IndiGo airines fly to all the destinations mentioned in this dataset. 
    - New Delhi to Cochin has the highest mean flight duration which is 817.85 minutes. Where as, Chennai to Kolkata flight only takes about 139.6 minutes on average with no lay overs.
    - Spice jet offers the cheapest prices between New Delhi and Cochin which is INR  5916.35 on average.
    - BOM airport has the highest number of layover flights considering all the destinations. 
3. AirFare_Data_Preprocessing.ipynb - Data transformation and encoding.
4. AirFare_ML.ipynb - Outlier handling and training a RandomForestRegressor.

| evaluation metrics | Value    | 
| :---:   | :---: |
| Training Error  |  0.95   |
| r2-score | 0.81   |
| MSE | 3538093.51   |
| MAPE | 13.06   |
| Accuracy | 86.93   |