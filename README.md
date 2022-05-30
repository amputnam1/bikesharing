## Bikesharing using NYC CitiBike data set

## Project Overview

The intention of this project is to analyze Citi Bike Data bike-sharing data from August 2019 in order to help build a solid business proposal for a similar program in Des Moines. One of the key stakeholders interested in this project would like to see a bike trip analysis. 

This analysis used Pandas in order to change the trip duration column from integer to datetime datatype. Once this datatype was converted, a set of visualizations were created in order to:
- Show the lenhth of time that bikes are checked out for all riders and genders.
- Show the number of bike trips for all riders and genders for each hour of each day of the week.
- Show the number of bike trips for each type of user and gender for each day of the week.


Tableau Analysis link: [Citi Bike Tableau Dashboard](https://public.tableau.com/app/profile/andrea.putnam/viz/NYCCitiBikeAnalysis_16538347257250/NYCCitiBikeAnalysis)

## Resources Used 
- Data sources:[Citi bike](https://ride.citibikenyc.com/system-data), 201908-citibike-tripdata.csv.zip
- Python 3.9.7, Anaconda, Jupyter Notebook, Tableau Public, Pandas

## Results

New York City Bike data visualizations for August 2019 

Ride Starting Locations
<img width="846" alt="Screen Shot 2022-05-30 at 10 28 54 AM" src="https://user-images.githubusercontent.com/93094173/171013166-efaba1d1-1a3d-4194-afa9-259d6567c47b.png">

<img width="569" alt="Screen Shot 2022-05-30 at 10 30 06 AM" src="https://user-images.githubusercontent.com/93094173/171013282-36b56798-e9dd-4aa9-97a4-50cceb0a85c7.png">

Trip duration by gender

<img width="852" alt="Screen Shot 2022-05-30 at 10 31 39 AM" src="https://user-images.githubusercontent.com/93094173/171013590-9d3b7822-e41e-41b4-82a3-c841564bb985.png">

Number of trips per hour by weekday

<img width="861" alt="Screen Shot 2022-05-30 at 10 32 56 AM" src="https://user-images.githubusercontent.com/93094173/171013835-3ec7b492-ff9e-459a-8d94-9a4149382b48.png">

 <img width="1187" alt="Peak hours of usage" src="https://user-images.githubusercontent.com/93094173/171019498-14a88195-7207-4218-869f-ce60430e8588.png">

Number of trips per hour, by weekday, by gender

<img width="1037" alt="Number of trips per hour by weekday by gender" src="https://user-images.githubusercontent.com/93094173/171019830-f95c4222-f40c-49bd-9a90-a66d6a398b68.png">

## Summmary

In summary, we can draw the following information based on the data and visualizations:

- There are over 2.3 million rides within the month of August 2019. 
- 65% of the users were male and 25% were female.
- 81% of riders were subscribers to CitiBike and the remaining 19% were not subscribers.
- It appears that the top starting locations were in busier areas such as downtown Manhattan.
- Peak hours of usage are from 5-7pm
- Younger riders typically had longer trip durations (however, there was a spike in duration for those born in 1933 and 1969, respectively.

Further, we can draw the findings that there is a high volume of bike sharing customers in New York in August 2019. It's likely that given it is a warm, summer months and that most of the ridership is between 5-7pm, we can infer that riders are likely taking advantage of the nice weather and using bikes as an alternate to public transportation. 

Two additional visualizations that would be helpful to include to tell the story of this data and provide additional insights to the stakeholders could include:

- Comparison of month data other than August to have a more accurate picture of ridership and a potential corelation to weather. This could also help inform whether a business in Des Moines or similar cold climates in the winter would be a viable business option.
- Review bike sharing data from a city that is closer in size, population, and climate to De Moines. While looking at the data for NYC provides a snapshot, it shouldn't necessarily drive business decisions as they have higher tourism and other factors to consider.
