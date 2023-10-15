# **Analysis of Customer Behaviours Over Car Insurance**
![ReadMe Image](https://github.com/nelettelouw/Car-Insurance/blob/main/Car%20Insurance%20Image.PNG))

**Author:** Nelette Louw
## **Business Problem:**
To analyze and predict whether a customer will/could submit an insurance claim.

## **Data Source:**
https://www.kaggle.com/datasets/sagnik1511/car-insurance-data

## **Description of Data:**
A company has shared it's annual car insurance data and consists of 19 features (as shown below) and 10 000 rows.
Each row represents the data of a customer and the feature "Outcome" indicates whether the customer has made an insurance claim or not (1 = Claimed, 0 = Not Claimed).

![ReadMe Image](https://github.com/nelettelouw/Car-Insurance/blob/main/Car%20Insurance%20Data%20Components.PNG)

The target is to analyse and predict customer behaviour - whether the customer will claim against their insurance or not. The problem statement will therefor be a binary classification problem.

## **Method**

- ### **Data Cleaning**
  - Deleted unnecessary columns
  - Deleted duplicate rows
  - Identified and addressed missing values
  - Identified and corrected inconsistencies in data for categorical values
  - Produced univariate visuals for the target and all features
  - Identified outliers
 
- ### **Exploratory Data Analysis**
    - Univariate Visualizations
    - Heatmap/Correlation Visualization
    - Multivariate Visualizations

- ### **Modelling**
    - KNeighbors Classifier
    - Logistic Regression
    - Logistic Regression with PCA

## **Analytical Insights**
![ReadMe Image](https://github.com/nelettelouw/Car-Insurance/blob/main/Insurance%20Claims%20(Age%20Group).PNG)

More ```Insurance claims``` are made by the ```Age Group``` 16-25 year than other age groups.

![ReadMe Image](https://github.com/nelettelouw/Car-Insurance/blob/main/Past%20Accidents.PNG)

When Past Accidents and Speeding Violations are compared, it shows that the more Speeding Violations customers have, the more likely it is that they also have been involved in Past Accidents.

![ReadMe Image](https://github.com/nelettelouw/Car-Insurance/blob/main/Driving%20Experience.PNG)

Claims made by customers gets lower with the more ```Years of Driving Experience``` a customer has. Customers who fall in the bracket ```10-19 years of Driving Experience``` shows to make the least claims overall.

## **The Best Model**
### **Logistic Regression with PCA**
  
**Metrics**
      
![ReadMe Image](https://github.com/nelettelouw/Car-Insurance/blob/main/Metrics%20of%20Best%20Model.PNG)

The production model that I would choose is the Logistic Regression with PCA due to the fact that it has the highest accuracy rate of 86%. PCA will also be an advantage when dealing with big data sets.

## **Recommendations**
  - It is recommended that the insurance company should pay close attention to all the correlations and relationships that's been shown in the visualizations when determining the insurance premium of a customer.
  - Customers in the age group 40-64 year will also mostly be the customers with most years of driving experience. To enhance and attracks more business, this age group's premiums could potentially be discounted.
