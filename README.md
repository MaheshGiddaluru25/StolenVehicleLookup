# StolenVehicleLookup.

# Overview
You are a data analyst working for a police department, and you have been provided with a dataset containing all the stolen vehicles data for New Zealand. Each record represents a single stolen vehicle, with data on vehicle type, make, year, colour, date stolen and region stolen. Your task is to perform data transformation functions like VLOOKUPs and INDEX-MATCH functions which will help us merge the data and identify different aspects in the dataset. 
Dataset
# Stolen Vehicle dataset
•	Vehicle_id: Unique ID of a stolen vehicle.
•	Vehicle_type: Types of vehicle of stolen vehicle
•	Make_id: Matches make id in the make-details table
•	Model_year: Model year of the stolen vehicle
•	Vehicle_desc: Description of the stolen vehicle
•	Color: Color of the stolen vehicle
•	Date_stolen: The date at which the vehicle got stolen
•	Location_Id: Matches location_id in the locations table
# Location dataset
•	Location_id: Unique ID of the region at which the stolen vehicle was located.
•	Region: Name of the Region
•	Country: Country where the region is located
•	Population: population of the region
•	Density: Density of the region (population 
# Make Details dataset
•	Make_id: Unique id of the make
•	Make_name: Name of the make
•	Make_type: type of make (standard or Luxury)

# Task to be performed
1.	Using the VLOOKUP function, populate the REGION and the COUNTRY column with the help of location dataset.
