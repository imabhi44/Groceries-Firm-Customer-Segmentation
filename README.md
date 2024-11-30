# Groceries-Firm-Customer-Segmentation
- Name - Abhishek Kumar
- Project - Grocery firm customer segmentation
- Skills - Aglomerative clustering, PCA, Data Visualisation , Exploratory Data Analysis ,profiling,  Machine Learning
- Tools -  Jupyter Notebooks , Python , Numpy , Pandas , Matplotlib , Seaborn , Sklearn
# The Dataset :
![image](https://github.com/user-attachments/assets/991b1c76-5a95-4f7a-8f5c-360ef8dcaa78)
# The Dataset :
- There are missing values in income
- Dt_Customer that indicates the date a customer joined the database is not parsed as DateTime
- There are some categorical features in our data frame; as there are some features in dtype: object). So we will need to encode them into numeric forms later.
- First of all, for the missing values, I am simply going to drop the rows that have missing income values.

# Introducing New features :  
![image](https://github.com/user-attachments/assets/3dd91686-6c0e-4501-b42f-512c7a821796)

There was few outliers in the dataset.
![image](https://github.com/user-attachments/assets/0d023502-292d-49d3-95b2-8b92e6b7c6e6)

# Data Preprocessing:
The following steps I have applied to preprocess the data:

- Label encoding the categorical features
- Scaling the features using the standard scaler
- Creating a subset dataframe for dimensionality reduction




