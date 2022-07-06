# Final-Project
Final Challenge 20

## 1. Decide on a topic, source data, and perform exploratory data analysis.

#### Topic: 

Relationship between crimes and location in 2021 at Austin, Texas

#### Source data:

The data for our project was retrieved from https://catalog.data.gov 
The specific data set is Crime Reports in the city of Austin, Texas https://catalog.data.gov/dataset/crime-reports-bf2b7

#### Perform exploratory data analysis

After the data was downloaded, it was filtered to better match the vision of the project. Columns that were not applicable to the dataset were deleted. The reamining columns are: 
  * Incident Number
  * Highest Offense Description
  * Occurred Date
  * Occurred Time
  * Report Date
  * Report Time
  * Location Type
  * Address
  * Zip Code
  * Census Tract
  * Clearance Date 
  * X-coordinate
  * Y-coodinate
  * Latitude
  * Longitude
  * Location (latitude and longitude) 

Next rows were deleted to only show the reportable crime data for the year 2021 in the city of Austin, Texas. After these filtering processes we had over 54000 records. 


## 2. Create a repository and establish individual branches for each team member.
We make main repository, "Final_Project" and each team member has one repositary 

![image](https://user-images.githubusercontent.com/100230706/177629420-4fe872f6-6f61-4b09-93c5-1835cc3ec5cf.png)


## 3. Create a mockup of a machine learning model.

<img width="966" alt="Screen Shot 2022-07-05 at 9 26 54 PM" src="https://user-images.githubusercontent.com/99656224/177447841-45fcbcd2-6f48-419b-854e-2401cd2eda57.png">


## 4. Create a mockup of a database.

The data was uploaded to Jupyter Notebook where null values were dropped. The shape of the remaining data is as follows: 
  
<img width="656" alt="image" src="https://user-images.githubusercontent.com/99268646/177450389-63334cb9-fd1d-4c2d-a9a3-18fc4bcab1f1.png">


## 5. Decide which technologies will be used.

We are going to use Machine learning and Jupyter notebook. Also we will use Map GeoJSON for showing which crime happened in which location and also compare the time between crimes.

![image](https://user-images.githubusercontent.com/100230706/177631021-dc5f7986-5b4c-4a66-af50-e126e8536562.png)

![image](https://user-images.githubusercontent.com/100230706/177631378-fbb2e99c-39b4-4fa6-8ffc-b330783b914b.png)



