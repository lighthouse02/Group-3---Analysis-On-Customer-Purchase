# Group-3---Analysis-On-Customer-Purchase

We have been provided with information about the customers' historical purchase as the amount of money spent, Number of inactive months and so on. Two columns `Potential_Customer` and `Cust_Last_Purchase` represent the customers' respond to the latest promotion. The column `Potential_Customer` represents if the customer purchased any product, and the column `Cust_Last_Purchase` represents the amount of this purchase and it is `Nan` if there has been no purchase.

## Objective
**Design a predictive model to determine the potential customers.** The target variable is `Potential_Customer`. 

**Attention:** Because the column `Cust_Last_Purchase` relates to the target variable `Potential_Customer`, need to exclude it from model.

# Table of Content

- JDS Capstone
- Data description
- Objective
- Submission Guideline
- Presentation Guideline
- Table of Content
- 0. Import necessary Packages
- 1. Load the Data into Pandas Dataframe
- 2. Data Cleaning
    - 2.1 How big is the dataset? (number of rows, features and total datapoints)
    - 2.2 What is the type of each column?
        - 2.2.1 Why columns such as `Cust_Last_Purchase` are `object` while they should be `float64`? Fix the type of the columns as it should be.
    - 2.3 Check data for duplicate rows and remove the duplicates
    - 2.4 Do we need `C_ID` in our analysis? Drop the columns you will not use in your analysis, if there is any.
- 3. Exploratory Data Analysis (EDA)
    - 3.1 Explore Categorical Variables
        - 3.1.1 Insight
        - 3.1.2 Solution
    - 3.2 Explore Relationship Between Categorical & Target Variable. Interpret the observation
        - 3.2.1. Insight
    - 3.3 Explore Numerical Variables
        - 3.3.1 Insight
        - 3.3.2 Check the Data for Missing Values
    - 3.4 Explore the Relationship between Numerical Variables & Target Variable. Interpret your observation
    - 3.5 Explore the Relationship between the columns and try to answer the following questions:
- 4. Feature Enginearing
    - 4.1 Add Some High Level Features and explore their relationship with the target variable
    - 4.2 Check Correlation between Numerical Variables
- 5. Feature Selection
- 6. Data PreProcessing
    - 6.1 Separate X (features) and y (target)
    - 6.2 Dummy Variables
    - 6.3 Split data to train/test
    - 6.4 Feature Scaling
    - 6.5 PCA on Numerical Columns only
- 7. Machine Learning
