# NY Citi Bike 
## Overview
The objective of this project was to provide information about the bicycle utilization patterns of NY Citi Bike customers for a client. The client is thinking of starting her own bicycle ride sharing business in Des Moines, IA. An analysis of data from August of 2019 was  specifically requested. The client will use this information to broker strategic conversations with potential investors. 
## Data Retrieval
The data that was used for this project was retrieved from Citi Bike Trip Histories, specific to August of 2019. Jupyter Notebook and Python with Pandas were utilized to create an additional csv data file that included a formatted date and time field for the trip duration. Both data sets were used to create the Tableau visualizations in this project. 
###### Jupyter Notebook File
![NYC_CitiBike_Challengeipynb_code](https://github.com/LleeMcD/bikesharing/blob/main/Resources/NYC_CitiBike_Challengeipynb_code.png)
###### Data Frame for Second Source File
![tripduration_pandas_update_dtstamp](https://github.com/LleeMcD/bikesharing/blob/main/Resources/tripduration_pandas_update_dtstamp.png)
## Analysis
#### Checkout Times
The data indicates that the total check out time duration for the majority of riders was 10 minutes. The peak checkout time for all riders was 5 minutes. The peak checkout time for male riders was at 5 minutes. The peak checkout time for female riders was at 6 minutes and the peak checkout time for riders of unknown gender was at 11 minutes.
###### Checkout Times by Gender

| GENDER  | 5        | 10      | 15     | 20     | 30     | 45     | 59     |
|---------|----------|---------|--------|--------|--------|--------|--------|
| ALL     | 146,752  | 106,954 | 66,769 | 45,515 | 21,346 | 3,858  | 1,122  |
| FEMALE  | 33,041   | 28,247  | 18,085 | 12,400 | 6,082  | 1,049  | 347    |
| MALE    | 108,087  | 71,049  | 41,571 | 26,251 | 11,511 | 1,898  | 413    |
| UNKNOWN | 5,624    | 7,298   | 7,113  | 6,864  | 3,753  | 911    | 362    |

![Checkout_all_1](https://github.com/LleeMcD/bikesharing/blob/main/Resources/Checkout_all_1.png)
![Checkout_gender_lines_2](https://github.com/LleeMcD/bikesharing/blob/main/Resources/Checkout_gender_lines_2.png)
#### Daily, Weekly  and Hourly Trips
The visualizations demonstrate that the majority of trips for all rider types were between:
- 8AM and 9 AM M-F
- 5PM and 7PM M-T-TH
- 9AM and 8PM SAT
- 9AM and 7PM SUN

Ride frequency patterns were noted to be similar between all gender types with a notable drop in usage for Wednesday afternoon and evening.
The frequency of trips by gender and user type per weekday demonstrates the highest usage on the following days for:
- Customers
  - Females: SUN-M-T, TH-F-SAT 
    - Saturday had the most rides: 27,503
    - Wednesday had the least rides: 6,024
  - Males: SUN-M-T, TH-F-SAT
	  - Saturday had the most rides: 40,280
    - Wednesday had the least number of rides: 12,427
  - Unknown: SUN-M-T, TH-F-SAT
	  - Saturday had the most rides: 55,257
    - Wednesday had the least number of rides: 12,704
- Subscribers
  -  Females: SUN-M-T, TH-F-SAT 
      - Thursday had the most rides: 88,192
      - Sunday had the least number of rides: 53,814
  - Males: M-T-W- TH-F-SAT
	    - Thursday had the most rides: 258,026
      - Sunday had the least number of rides: 131,524
   - Unknown: M-T-W-TH-F-SAT
	    - Saturday had the most rides: 6,084
      - Sunday had the least number of rides: 3,536
![Weekly_trips_each_hr_3](https://github.com/LleeMcD/bikesharing/blob/main/Resources/Weekly_trips_each_hr_3.png)
![Weekly_trips_each_hr_gender_4](https://github.com/LleeMcD/bikesharing/blob/main/Resources/Weekly_trips_each_hr_gender_4.png)
![Weekly_trips_each_day_gender_user_type_5](https://github.com/LleeMcD/bikesharing/blob/main/Resources/Weekly_trips_each_day_gender_user_type_5.png)
![August_hrs_6](https://github.com/LleeMcD/bikesharing/blob/main/Resources/August_hrs_6.png)
#### Top Starting and Stopping Locations
Understanding both when and where people use Citi Bike will help plan the Des Moines pilot. The top starting and ending locations happen to be in areas where there are a large number of tourists and locals alike. It could be benefical for the client to investgate tourist traffic for popular destinations in DesMoines, as well as locations of companies with large numbers of employees, who could use the rideshare services for commuting purposes during the warmer months of the year.
![Top_starting_7](https://github.com/LleeMcD/bikesharing/blob/main/Resources/Top_starting_7.png)
![Top_ending_8](https://github.com/LleeMcD/bikesharing/blob/main/Resources/Top_ending_8.png)
#### Recommendations
Additional visualizations that could be useful to the client include:
- Population demographic comparison with target site Des Moines, IA. Age, culture, health and financial information could inform advertising strategies and also provide insight for underwring liability insurance for the company.
- Bike utilization frequency should also be considered because bike maintenance will likely be one of the biggest expenses with a ride sharing company. 

#### Tableau Dashboard 
The Tableau workbook and story visualizations for this project can be accessed by clicking on the link below and selecting the visualtization titled "NYC_Citibike_Challenge_Viz"


[NYC Bike Project Dashboard](https://public.tableau.com/app/profile/lleemcd8694)

#### Resources

