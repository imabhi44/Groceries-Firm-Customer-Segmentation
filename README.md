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
# Dimensionality Reduction:
Steps in this section:

- Dimensionality reduction with PCA
- Plotting the reduced dataframe
- Dimensionality reduction with PCA
  
  ![image](https://github.com/user-attachments/assets/a622e0d1-c16a-4426-abd5-0aea0b97d2ca)

  # Clustering:
  ![image](https://github.com/user-attachments/assets/380d1da3-1989-4800-ad39-4b3a042aa26e)

  ![image](https://github.com/user-attachments/assets/23b71cb4-4ee7-4db2-ac83-3d380a11bd5f)
  
# EVALUATING MODELS:
- Since this is an unsupervised clustering. We do not have a tagged feature to evaluate or score our model. The purpose of this section is to study the patterns in the clusters formed and determine the nature of the clusters' patterns.

- For that, we will be having a look at the data in light of clusters via exploratory data analysis and drawing conclusions.
  ![image](https://github.com/user-attachments/assets/98a94a40-a09c-41fd-8fc7-07cb02bbf4ee)
  ![image](https://github.com/user-attachments/assets/8583f6e3-98fe-43cf-890e-906b4a0b324d)

- group 0: high spending & average income.
- group 1: low spending & low income.
- group 2: high spending & high income.
- group 3: low spending & high income.
Next, I will be looking at the detailed distribution of clusters as per the various products in the data. Namely: Wines, Fruits, Meat, Fish, Sweets and Gold
![image](https://github.com/user-attachments/assets/78eafd2d-2555-4fae-a554-cabcc4514ed7)

![image](https://github.com/user-attachments/assets/7fd742dc-3001-4a51-9350-1970ed9a85b4)

- There has not been an overwhelming response to the campaigns so far. Very few participants overall. Moreover, no one part take in all 5 of them. Perhaps better-targeted and well-planned campaigns are required to boost sales
  
![image](https://github.com/user-attachments/assets/f7cdeb3a-2574-4ad9-8140-0410f75ba416)
- Unlike campaigns, the deals offered did well. It has best outcome with cluster 0 and cluster 3. However, our star customers cluster 2 are not much into the deals. Nothing seems to attract cluster 1 overwhelmingly

# After Profiling:
Points to be noted:

- The following information can be deduced about the customers in different clusters.

# Cluster_Number_0

- Are definitely a Parent.
- At the max have 4 member in the family and at least 2.
- Most have a teenager at home.
- Relatively Older
  
# Cluster_Number_1

- Are definitely not a Parent.
- At max 3 members in the family.
- Span all ages.

# Cluster_Number_2

- Definitely not a Parent
- At max 2 members in the family
- Majority have no kid
- Relatively older

# Cluster_Number_3

- They are definitely a parent
- At max 5 members in the family size and at least 2.
- Majority of them have a teenager
- Relatively Older.








