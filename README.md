# NY Citi Bike - draft
## Overview
The objective of this project was to provide information about bicycle utilization patterns of NY Citi Bike customers for a client. The client is thinking of starting her own bicycle ride sharing business in Des Moines, IA. An analysis of data from August of 2019 was  specifically requested. The client will use this information to broker a strategic conversation with investors. 
## Data Retrieval
The data that was used for this project was retrieved from Citi Bike Trip Histories, specific to August of 2019.  A Panda’s data frame was utilized to create an additional csv  data file that included a formatted date and time field for the trip duration. Both data sets were used to create the Tableau visualizations in this project. 
###### Jupyter Notebook File
![NYC_CitiBike_Challengeipynb_code](https://github.com/LleeMcD/bikesharing/blob/main/Resources/NYC_CitiBike_Challengeipynb_code.png)
###### Data Frame
![tripduration_pandas_update_dtstamp](https://github.com/LleeMcD/bikesharing/blob/main/Resources/tripduration_pandas_update_dtstamp.png)
## Analysis
###### Checkout Times
The total number of riders for August, 2019 was 2,344,224. The data indicates that the check out time for the majority of these riders was 10 minutes, with the peak number of checkouts for all riders at 5 minutes. The majority of chekouts were made by males with a peak number of 108,087 at 5 minutes. The peak number of female riders was 34,151 at 6 minutes and the peak number of rides for gender unknown was 7,389, at 11 minutes.

| GENDER  | 5        | 10      | 15     | 20     | 30     | 45     | 59     |
|---------|----------|---------|--------|--------|--------|--------|--------|
| ALL     | 146,752  | 106,954 | 66,769 | 45,515 | 21,346 | 3,858  | 1,122  |
| FEMALE  | 33,041   | 28,247  | 18,085 | 12,400 | 6,082  | 1,049  | 347    |
| MALE    | 108,087  | 71,049  | 41,571 | 26,251 | 11,511 | 1,898  | 413    |
| UNKNOWN | 5,624    | 7,298   | 7,113  | 6,864  | 3,753  | 911    | 362    |



![Checkout_all_1](https://github.com/LleeMcD/bikesharing/blob/main/Resources/Checkout_all_1.png)
![Checkout_gender_lines_2](https://github.com/LleeMcD/bikesharing/blob/main/Resources/Checkout_gender_lines_2.png)
###### Daily, Weekly  and Hourly Trips
![Weekly_trips_each_hr_3](https://github.com/LleeMcD/bikesharing/blob/main/Resources/Weekly_trips_each_hr_3.png)
![Weekly_trips_each_hr_gender_4](https://github.com/LleeMcD/bikesharing/blob/main/Resources/Weekly_trips_each_hr_gender_4.png)
![Weekly_trips_each_day_gender_user_type_5](https://github.com/LleeMcD/bikesharing/blob/main/Resources/Weekly_trips_each_day_gender_user_type_5.png)
![August_hrs_6](https://github.com/LleeMcD/bikesharing/blob/main/Resources/August_hrs_6.png)
###### Top Starting and Stopping Locations
![Top_starting_7](https://github.com/LleeMcD/bikesharing/blob/main/Resources/Top_starting_7.png)
![Top_ending_8](https://github.com/LleeMcD/bikesharing/blob/main/Resources/Top_ending_8.png)
###### Tableau Dashboard 
The Tableau workbook and story visualizations can be accessed by clicking on this link:
[NYC Bike Project Dashboard](https://public.tableau.com/app/profile/lleemcd8694)

