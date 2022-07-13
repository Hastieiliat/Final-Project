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

## 1. GitHub Repository

In this segment, we are going to present:

#### Selected topic
Relationship between crimes and location in 2021 at Austin, Texas

#### Reason topic was selected
We are interested to see the number of crime and location in 2021 at Austin, Texas. 


#### Description of the source of data,  Questions the team hopes to answer with the data, Description of the data exploration phase of the project, and Description of the analysis phase of the project

Explained in the first segment

The responsibilities of each team member in the second segments are:

![image](https://user-images.githubusercontent.com/100230706/178614010-04f42b86-6f64-4539-9d30-48567534c9ca.png)

## 2. Machine Learning Model 
#### Description of preliminary data preprocessing

![image](https://user-images.githubusercontent.com/100230706/178618516-9ea36ccf-805d-4364-939d-e009cc77085f.png)


#### Description of preliminary feature engineering and preliminary feature selection, including the decision-making process

![image](https://user-images.githubusercontent.com/100230706/178618802-49726d89-559d-4a0c-86c2-9f8b61e5be19.png)

#### Description of how data was split into training and testing sets

![image](https://user-images.githubusercontent.com/100230706/178619012-836608c6-7a67-4ebf-9a01-67554971b08d.png)

#### Explanation of model choice, including limitations and benefits

![image](https://user-images.githubusercontent.com/100230706/178619371-c233edc0-3cac-4874-a0a7-3689c66f404e.png)



## 3. Database Integration

#### Database stores static data for use during the project

![image](https://user-images.githubusercontent.com/100230706/178621765-24ebceea-56ad-4000-9392-af35641d555c.png)

#### Database interfaces with the project in some format (e.g., scraping updates the database)

![image](https://user-images.githubusercontent.com/100230706/178622018-c65fe195-7391-4fff-be90-1159a0fb7bd7.png)


#### Includes at least two tables (or collections, if using MongoDB)

![image](https://user-images.githubusercontent.com/100230706/178622176-4c7049a4-91a2-48d7-9e13-173fb1d8727c.png)


#### Includes at least one join using the database language (not including any joins in Pandas)

![image](https://user-images.githubusercontent.com/100230706/178622226-e9095f46-dc47-4ae3-a3b4-6928b9777c56.png)


#### Includes at least one connection string (using SQLAlchemy or PyMongo)

![image](https://user-images.githubusercontent.com/100230706/178622280-a8cef433-6e18-4eae-a59d-65d8c2f89c19.png)

![image](https://user-images.githubusercontent.com/100230706/178622320-47edc957-a742-43a7-b725-c4dce968cb63.png)

