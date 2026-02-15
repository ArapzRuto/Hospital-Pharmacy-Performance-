# Hospital-Pharmacy-Performance
Hospital &amp; Pharmacy Performance  Power BI Analysis

**Overview**

The data set consisted three relational tables, Patients (Patient_ID	Patient_Name	Gender	Age	County), Visits (Visit_ID	Patient_ID	Visit_Date	Department	Diagnosis
Length_of_Stay_Days) and Pharmacy Transactions (Transaction_ID	Visit_ID
Drug_Name	Drug_Category	Quantity	Unit_Price	Total_Cost).  The dataset was loaded into Power BI for data cleaning, data modelling, and data analysis. 

**Data Cleaning**

Visit ID, Patient ID. Transaction ID changed to Text data type. 
The data set had no duplicates, missing values, or errors. 
Visit date changed to short format


**Key Questions Answered**

**1.	Which diseases are most common across counties?**
![Quiz 1](https://github.com/ArapzRuto/Hospital-Pharmacy-Performance-/blob/main/screenshots/Quiz%201.jpg)

Kiambu- Diabetes and Typhoid, each with 13 cases reported.
Kisumu-Hypertension with 16 cases reported.
Mombasa- Flu with 11 cases reported.
Nairobi-Pneumonia with 9 cases reported.
Nakuru- Flu with 9 cases reported.
Uasin Gishu- Flu with 15 cases reported.

**2.	Does a higher number of patient visits always lead to higher pharmacy revenue?**

![Quiz 2](https://github.com/ArapzRuto/Hospital-Pharmacy-Performance-/blob/main/screenshots/Quiz%202.jpg)

No, a higher number of patient visits does NOT always lead to higher pharmacy revenue. Why? Because revenue depends on: Type of medication prescribed, Quantity dispensed, Unit price, and whether visits result in prescriptions at all 

**3.	Which departments generate the highest pharmacy costs?**

![Quiz 3](https://github.com/ArapzRuto/Hospital-Pharmacy-Performance-/blob/main/screenshots/Quiz%203.jpg)

Inpatient department with a total pharmacy cost of 94759

**4.	Are there age groups that consume more medication than others?**

![Quiz 4](https://github.com/ArapzRuto/Hospital-Pharmacy-Performance-/blob/main/screenshots/Quiz%204.jpg)

Yes. It was evident that patients in the age group 81-90 are the highest consumers of medication (39772), while those in the age group 41-50 are the lowest consumers of medication (18966). 

**5.	Are some diagnoses associated with more extended hospital stays but lower pharmacy spending?**

![Quiz 5](https://github.com/ArapzRuto/Hospital-Pharmacy-Performance-/blob/main/screenshots/Quiz%205.jpg)

No. Some diagnoses, such as Malaria, with a lower average length of stay,1.05, reported high average pharmacy spending, 879.63, compared to Hypertension, which had a higher average length of stay, 1.72, but  a pharmacy spending of 734.37

**Executive Dashboard and Insights**

![Hospital and Pharmacy Dashboard](https://github.com/ArapzRuto/Hospital-Pharmacy-Performance-/commit/c5e6603e1fcd4da70b2e7fb77ae2b7f9016e03e5#diff-64e662f6667f5327bd33e3ee341cd3d91122262677d3efceb52f8341f9e3d704)





 
The dashboard created revealed critical insights regarding hospital performance from the perspectives of patients, physicians, and pharmacy transactions. 

**a)**	The disease trend over time indicated that in 2024, Diabetes (April 8 cases) and Hypertension (March 8 cases) had the highest case counts. Alternatively, Flu (February 1 case) and Hypertension (October 1 case) reported the fewest cases. 

**b)**	The pharmacy cost breakdown indicated that Malaria drugs are the most consumed, with a total cost of 54950. Alternatively, Hypertension drugs are less consumed, with a total cost of 36968.

**c)**	Kiambu County has the highest percentage of cases reported per department compared to the other counties.
