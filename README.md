# Final-Project
# First Segment Challenge 20

## 1. Decide on a topic, source data, and perform exploratory data analysis.

#### Topic: 

Relationship between crimes and location in 2021 at Austin, Texas

#### Source data:

The data for our project was retrieved from https://catalog.data.gov 
The specific data set is Crime Reports in the city of Austin, Texas https://catalog.data.gov/dataset/crime-reports-bf2b7
Our Data is "Crime_Reports.csv" file. 

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
With our knowledge of machine learning and neural networks, we used the features in the provided dataset to create a binary classifier that is capable of predicting whether applicants will be successful for helping police to predict the crime at specific time zone and locations.

The preprocessed data is split into features and target arrays, training and testing datasets and also the numerical values have been standardized using the StandardScaler() module. 

![image](https://user-images.githubusercontent.com/100230706/177637814-2d98d2ed-16c7-4c17-adf1-abc6ad5327a1.png)


Create a 3D scatter plot using the Plotly Express scatter_3d() function to plot the three clusters from the DataFrame.

<img width="966" alt="Screen Shot 2022-07-05 at 9 26 54 PM" src="https://user-images.githubusercontent.com/99656224/177447841-45fcbcd2-6f48-419b-854e-2401cd2eda57.png">

Also, we create an elbow curve to find the best value for K:

<img width="947" alt="Screen Shot 2022-07-06 at 4 18 32 PM" src="https://user-images.githubusercontent.com/99656224/177635808-4de8b167-9531-4412-9451-f49432dabd7e.png">


## 4. Create a mockup of a database.

The data was uploaded to Jupyter Notebook where null values were dropped. The shape of the remaining data is as follows: 
  
<img width="656" alt="image" src="https://user-images.githubusercontent.com/99268646/177450389-63334cb9-fd1d-4c2d-a9a3-18fc4bcab1f1.png">



## 5. Decide which technologies will be used.






We are going to use Machine learning and Jupyter notebook. Also we will use Map GeoJSON for showing which crime happened in which location and also compare the time between crimes.

![image](https://user-images.githubusercontent.com/100230706/177631021-dc5f7986-5b4c-4a66-af50-e126e8536562.png)

![image](https://user-images.githubusercontent.com/100230706/177631378-fbb2e99c-39b4-4fa6-8ffc-b330783b914b.png)



# Second Segment Challenge 20

In this segment, we are going to present:

### Selected topic
Relationship between crimes and location in 2021 at Austin, Texas

### Reason topic was selected
We are interested to see the number of cr
### Description of the source of data
### Questions the team hopes to answer with the data
### Description of the data exploration phase of the project
### Description of the analysis phase of the project



![image](https://user-images.githubusercontent.com/100230706/178614010-04f42b86-6f64-4539-9d30-48567534c9ca.png)
