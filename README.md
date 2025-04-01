____________________________________________________
____________________________________________
# <center>MONTGOMERY COUNTY CRIME ANALYSIS<center>
_______________________________________
__________________________________
### Overview
This project analyses crime data from Montgomery County, focusing on various aspects such as crime types, geographical distribution, temporal patterns, and correlations. The analysis aims to provide insights into crime trends and help in formulating effective crime prevention strategies.

### Dataset
The dataset used in this analysis is Crime_Dataset_Coursework1.csv, which contains detailed information about crime incidents in Montgomery County from 2018 to 2021.
Data Loading and Preprocessing

- Loading the Dataset: The dataset is loaded using pandas.read_csv().
- Data Cleaning: Various data cleaning operations are performed, including handling missing values, removing duplicates, renaming columns, changing data types, and filtering out outliers.

## Analysis and Visualization
Descriptive Statistics
- Summary statistics of the dataset are calculated to understand the distribution and central tendencies of the data.

**Data Cleaning Processes**
- Check DataFrame Dimensions: df.shape
- Display DataFrame Info: df.info()
- Identify Missing Values: df.isna().sum()
- Drop Rows with Missing Values: df.dropna()
- Fill Missing Values: df.fillna(value)
- Remove Duplicates: df.drop_duplicates()
- Rename Columns: df.rename(columns={'old_name': 'new_name'})
- Change Data Types: df['column'] = df['column'].astype('dtype')
- Handle Outliers: Using the Interquartile Range (IQR) method.

**Feature Engineering**
- Extracting Year, Month, and Hour: From the Start_Date_Time column to facilitate time-based analysis.
- Filtering Invalid Coordinates: Rows with latitude or longitude equal to zero are removed.

______________________________________________
_____________________________________________
## RESEARCH QUESTIONS AND VISUALIZATIONS

### 1.	Most Prevalent Types of Crimes
![image](https://github.com/user-attachments/assets/81ce5f93-ea4c-433b-9dbc-bea35dac499b)  ![image](https://github.com/user-attachments/assets/e19409ac-2ff0-4a78-8684-dcb26995d42d)
__________________

### 2.	Crime Rates Across Police Districts:
![image](https://github.com/user-attachments/assets/a7a126ea-2601-4fe8-a918-1d1328e98d6f)    ![image](https://github.com/user-attachments/assets/33ae6cd7-0bf2-45e6-a684-90eb9ae9e4b7)
_______________

### 3.  Correlation Between Time of Day and Crime Types:
![image](https://github.com/user-attachments/assets/439b2d47-c56b-4e2d-a42b-2cbaa91015a6) : ![image](https://github.com/user-attachments/assets/710dc3e4-c742-4ad2-ba73-82041348168b)
_________________

### 4.	Geographical Areas with Highest Property Crimes:
![image](https://github.com/user-attachments/assets/29ca21d3-69c9-49dc-8374-08b13d6664ee)  ![image](https://github.com/user-attachments/assets/aab9d8a8-1558-4156-b41c-120f9553153d)
__________________________

### 5.	Seasonal Patterns in Crime Rates:
![image](https://github.com/user-attachments/assets/708fb59e-4c08-4a1d-8a4b-1a9a28ab7b46)    ![image](https://github.com/user-attachments/assets/aae8f016-2e28-4479-9735-a0ddbf6c6cf6)
_______________________

### 6.	Distribution of Drug-Related Offenses:
![image](https://github.com/user-attachments/assets/fdc2310e-fbc3-4dad-a67b-6f3256fed5da)   ![image](https://github.com/user-attachments/assets/b608e5c7-5670-4287-ad1d-54d49940d6fb)
___________________________

### 7.	Relationship Between Crime Types and Locations:
![image](https://github.com/user-attachments/assets/5eb26a4b-4ba5-4432-b132-9c95685d062f)    ![image](https://github.com/user-attachments/assets/14199c01-6129-4f17-ae7a-aaafa8f15ae9)
________________________

### 8.	Trends in Motor Vehicle Thefts:
![image](https://github.com/user-attachments/assets/ed194301-04e5-4ee3-be33-16d8d0fbc0d0)   ![image](https://github.com/user-attachments/assets/dbb89365-29cf-45a1-a9f8-e66452e29761)
___________________________

9.	Comparison of Violent and Property Crimes:
![image](https://github.com/user-attachments/assets/140f6a60-a2f4-4d91-8ca3-592a52272870)   ![image](https://github.com/user-attachments/assets/0ce4a0f7-5d92-4f3a-b6df-1f56df485733)
___________________________________

10.	Trends in Overall Crime Rates by Police District: 
![image](https://github.com/user-attachments/assets/b8aecbf4-5fcb-4569-8d2c-874c1da79e2e)   ![image](https://github.com/user-attachments/assets/b2c8e08d-964c-4493-bb0a-377238d97fa0)

_____________________________________________
_________________________________________________________________
___________________
# SUMMARY AND CONCLUSION
___________________
This analysis of Montgomery County crime data from 2018 to 2022 revealed several key insights:
1.	**High Crime Areas:** Silver Spring consistently had the highest crime rates, followed by Bethesda and Wheaton.
2.	**Temporal Patterns:** Property crimes peaked in the evening, while violent crimes were more evenly distributed throughout the day.
3.	**Hotspots:** Silver Spring was a major hotspot for both property crimes and drug offenses.
4.	**Motor Vehicle Thefts:** These thefts increased significantly in 2021, marking the highest recorded incidents.
5.	**Crime Distributions:** Property crimes were generally more frequent than violent crimes, with a notable correlation between the two.
6.	**District-Level Changes:** Some districts showed significant changes in crime rates, indicating areas where interventions have been effective or are needed.

## Insights for Law Enforcement
- **Targeted Patrolling:** Focus on hotspots like Silver Spring and Wheaton.
- **Resource Allocation:** Efficiently allocate resources based on crime trends.
- **Community Programs:** Develop programs tailored to the unique crime patterns of each district.

## Limitations and Future Research
- Reporting Biases: Potential underreporting or inconsistencies in crime data.
- Continuous Updates: Regular data updates are necessary.
- Socio-Economic Factors: Future research should include socio-economic indicators for a more comprehensive analysis.

This project highlights the potential of data science in enhancing public safety, providing a model for similar analyses and contributing to data-driven crime prevention strategies.

### License
This project is licensed under the MIT License.
