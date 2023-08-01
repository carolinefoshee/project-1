# PROJECT 1 - WHAT DETERMINES HEALTH INSURANCE COST

TEAM MEMBERS: Caroline Foshee, Christian Zaner, Sivangi Raychoudhury

We have been given a task of finding a good dataset for our project and do further calculations and analysis on that dataset. For this purpose we decided to use Kaggel.com and found the dataset of our interest. The link to our dataset .csv file is https://www.kaggle.com/datasets/mirichoi0218/insurance 

PROJECT OBJECTIVE: 
The main aim of this project is to predict medical costs charged by health insurance companies based on various factors and also to analyse how these factors are related to the medical charges. Here the independent features are age, gender, body mass index (BMI), number of children, smoking status and region. The dependent feature is medical costs charged by insurance company which is labelled as charges. We reaised the following questions from the dataset, which was our aim.
1. Which independent variables are correlated with each other?
2. Which factors influence insurance cost the most?
3. Why these factors influence the insurance cost? 

STEP 1: 
After the .csv file got downloaded from Kaggel.com, we imported the csv into pandas dataframe, using Python Pandas library and Jupyter notebook. Other required dependencies are imported too at this point of time. Then, we cleaned the dataset by finding and deleting any null values and duplicated rows. Once the dataset got cleaned, we got our final dataframe as insurance_df, with seven columns, i.e age, sex, bmi, children, smoker, region and charges, and with 1337 rows of data. 

STEP 2: 
The distribution was plotted individually for all the variables in the dataset, to give an idea of how the dataset looks like. Since, we have only the charges column which is the only dependent variable, a box plot was created. In the same box plot, lots of outliers are found, which are not actually the outliers but the data information for the people with smoking habits. So, we decided not to filter those information as outliers. Rather, we divided our analysis into two groups: Smokers and Non-smokers. 

STEP 3: 
The next step was to find the relationship between the independent variables. The calculations and plots were made between 
1. Age and BMI
2. Region and smokers
3. Gender and smokers
4. Gender and BMI

STEP 4:
The relationship between the independent variables and dependent variable was calculated and to what degree they affect the insuarnce cost was determined. For this purpose the following plots were graphed,
1. BMI Vs Insurance cost (For Smokers and Non-Smokers)
2. Age Vs Insurance cost (For Smokers and Non-Smokers)
3. Smoking Vs Insurance cost
4. Family size Vs Insurance cost (For Smokers and Non-Smokers)
5. Gender Vs Insurance cost
6. Regions Vs Insurance cost

The final written analysis was uploaded as Analysis-file to this repository. 


