# School_District_Analysis

## Project Overview
Maria the chief data scientist for a city school district is reponsible for analyzinf information from a variety of sources, and in a variety of formats. In this role, she is tasked with preparing all standardized test data for analysis, reporting and presentatio to provide insights about performance trends and patterns. These insights are used to inform discussions and strategic decisions at the school and district level. For this project we helped Maria analyze data on student funding and students' standarized test school.We had access to every student's math and reading scores as well as various information on schools they attend. 

One of the main pourposes of the project was to aggregate the data and showcase trends in school performance. This analysis will assist the school board and superintendent in making decision regarding the school budgets and priorites. 

Nevertheless, after we finished the analysis the school board notified Maria that students' database file showed evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Therefore, the math and reading scores from Thomas High School were replaced with NaNs, keeping the rest of the data intact, and therefore the school distirct analysis was rerun. 

## Resources

- Data Source: schools_complete.csv, students_complete.cvs

## Results

- **How is the district summary affected?**

There was no significant change in district summary once  students' math and reading scores were marked as NaN. In the average math score we can observe a 0.1% decrease, on the other hand in the average reading score there was no change. In the math passing percentage we can observe a decrease of %0.2, and in the reading passing percentage a decrease of %0.3. Finally in the overage percentage we can see a decrease of %0.1.

_Original Data Base_

<img width="794" alt="Original_data_summary" src="https://user-images.githubusercontent.com/107893200/181655907-e584c158-dd4e-43b1-94a5-253ccaf6d14e.png">


_Updated Data Base_

<img width="795" alt="Modified_district_summary" src="https://user-images.githubusercontent.com/107893200/181655922-c255772f-bee7-48b9-a454-e59c9175cb51.png">

- **How is the school summary affected?**
- **How does replacing the ninth graders' math and reading scores affected Thomas High School's performance relative to the other schools?**


- **How does replacing the ninth-grade scores affected the following:**

  - **Math and reading scores by grade**
  
By replacing the ninth grade scores, Tomas High School lost its position as one of the schools with the highest percentage of reading scores, as it had 83.7%. In the new database the top school remains Shelton High School.

_Original Data Base_

<img width="437" alt="original_reading_scores" src="https://user-images.githubusercontent.com/107893200/181668857-0bf16adb-4098-45cf-a85a-e659739925c7.png"> 

_Updated Data Base_

<img width="435" alt="modified_reading_score" src="https://user-images.githubusercontent.com/107893200/181668881-6391d754-fa3b-4369-8084-6254abb90880.png">

As for the percentage of ninth grade math scores, Thomas High School was also affected, since it lost the third position with a percentage of 83.59%. In this category the best school is Holden High School.

_Original Data Base_

<img width="436" alt="original_math_scores" src="https://user-images.githubusercontent.com/107893200/181669474-3153f8e8-2a06-4168-9ce0-e89725d2c93d.png">

_Updated Data Base_

<img width="436" alt="modified_math_scores" src="https://user-images.githubusercontent.com/107893200/181669493-3225a742-5a9e-4f8d-a9e3-534df15088e6.png">

  - **Scores by school spending**
  
Regarding the review of the percentages according to school spending, the alterations that we can identify are located in the group $631-645, the group to which Thomas High School belongs. In the average math score there was a decrease of 0.01%, while in the average reading score there was a 0.01% increase. In the percentage of passing math there was a decrease of 0.02%, while in the percentage of passing reading there was a more significant decrease of 0.08%. Similarly in the percentage of overall passing there was a decrease of 0.08%. 

_Original Data Base_

<img width="793" alt="original_shool_spending" src="https://user-images.githubusercontent.com/107893200/181666736-9ab10772-d04c-4d8e-99da-4756cc819fbb.png">

_Updated Data Base_

<img width="796" alt="modified_school_spending" src="https://user-images.githubusercontent.com/107893200/181666751-075c03cb-733a-4e48-8c7a-8fb2792da735.png">

  - **Scores by school size**
  
Regarding the review of the percentages according to school size, the changes that we can identify are located in the Medium group (1000-1999), the group to which Thomas High School belongs. In the average math score there was a decrease of %0.01, while in the average reading score there was a 0.01% increase. In the percentage of passing math there was a decrease of 0.01%, while in the percentage of passing reading there was a more significant decrease of 0.06%. Similarly in the percentage of overall passing there was a decrease of 0.07%. 

_Original Data Base_

<img width="630" alt="Original_schoolsize" src="https://user-images.githubusercontent.com/107893200/181665727-264ed2cf-d12a-4686-b806-8834c92dc746.png">

_Updated Data Base_

<img width="758" alt="modified_schoolsize" src="https://user-images.githubusercontent.com/107893200/181665738-7d1882a2-f3d9-4e2c-95db-9280c6508c7a.png">

  - **Scores by school type**
  
In the case of the data corresponding to the Scores by school type we can observe few changes. Thomas High School falls into the Carter school type category and this is where we can find certain variations. Regarding the average math score the percentage decrease 0.01%, while in the average reading score we can see a slight increase of 0.01%. On the other hand, in the passing math percentage we can see a decrease of 0.01% and in the passing reading percentage we can see a decrease of %0.03. Finally, the overall passing percentage suffered a decrease of 0.04%.

_Original Data Base_
  
  <img width="620" alt="Original_school_type" src="https://user-images.githubusercontent.com/107893200/181661665-4d43a2ab-e0ea-4473-8764-7f75a023df59.png">

_Updated Data Base_

  <img width="714" alt="Modified_school_type" src="https://user-images.githubusercontent.com/107893200/181661674-3177edae-f96f-4ad1-88dd-bbf812a55f72.png">

## Summary

Following the review of the information presented previously, here is a summary of four changes in the school district's updated analysis after reading and math scores for ninth grade at Thomas High School have been replaced by NaNs.
