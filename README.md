# Smart-water-monitoring-systems
Participated in Hacker-Earth ML Challenege 

Problem
Water scarcity is an increasingly global issue, with urban households playing a major role in water wastage due to inefficient consumption habits. Traditional water meters provide only total usage data without insights into consumption patterns, making it difficult for homeowners to optimize their water usage effectively. Smart water monitoring systems, powered by machine learning, can help households predict their water consumption and adopt conservation measures.

Task

The goal of this project is to develop a Machine Learning model that predicts daily water consumption for individual households based on historical usage patterns, household characteristics, weather conditions, and conservation behaviors.

Dataset description

The dataset folder contains the following files: 

train.csv: 14000 x 12
test.csv: 6000 x 11
sample_submission.csv: 5 x 2
The columns provided in the dataset are as follows:

Column name

Description

Timestamp	Represents a unique timestamp of an entry
Residents	Represents the number of people living in the household
Apartment_Type	Represents the type of apartment
Temperature	Represents the average temperature of that time period
Humidity	Represents the average humidity of that time period
Water_Price	Represents the water price for that time period
Period_Consumption_Index	Represents the relative water usage for each 8-hour period
Income_Level	Represents the income level of household
Guests	Represents the number of guests
Amenities	Represents the types of amenities available in the household
Appliance_Usage	Represents whether water appliances are being used or not 
Water_Consumption	Represents the consumption of water in that period
Evaluation metric

score = max(0,100- np.sqrt(metrics.mean_squared_error(actual,predicted)))


My score:92
