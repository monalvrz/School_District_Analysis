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

The other schools were not negatively affected by the database modifications. What was affected was the positions that each school obtained in the following columns: Average Math Score, Average Reading Score, %Passing Math, %Passing Reading and %Overall Passing. The top 5 schools with the best Overall Passing was modified since Thomas High School is no longer in that ranking. Now the best schools in this category are: Cabrera High School with 91.33%, Griffin High School with 90.59%, Pena High School with 90.54%, Wilson High School with 90.58% and Shelton High School with 89.89%.

_Original Data Base_

<img width="784" alt="original_perschool_summary" src="https://user-images.githubusercontent.com/107893200/181680331-8d715a58-5268-49c2-a78f-6b81f942deca.png">


_Updated Data Base_

<img width="794" alt="modified_perschool_summary" src="https://user-images.githubusercontent.com/107893200/181680375-66f76ab8-c6e5-453a-abd3-dd3b5d9f5ef6.png">


- **How does replacing the ninth graders' math and reading scores affected Thomas High School's performance relative to the other schools?**

The substitution of math and reading scores for ninth graders affected Thomas High School's scores relative to the other schools. The scores that varied were: First in the BLA category the percentage decreased 0.06%. While in the average reading score category it increased 0.05%. In the % passing math category the percentage dropped 0.09% and in the % passing reading category it dropped 0.029%, while in the %overall passing category it decreased 0.31%.

With the updated information these are the top three high schools in each category:

    - Average Math Score: Pena High School 83.83%, Holden High School 83.80% and Wright High School 83.97%
    
    - Average Reading Score: Pena High School 84.04%, Wilson High School 83.98% and Cabrera High School 83.97%
    
    - % Passing Math: Pena High Shchool 94.13%, Cabrera High School 94.13% and a tie between Wilson High School 93.86% and Shleton High School          93.86%
    
    - % Passing Reading: Griffin High School 97.13%, Cabrera High School 97.03% and Thomas High School 97.01% 
    
    - % Overall Passing: Cabrera High School 91.33%, Griffin High School 90.59% and Pena High School 90.54%
    
    
In the original database Thomas High School was only among the top schools in the Overall Passing category. After the update of the data, its Overall Passing percentage dropped and its %Passing reading increased. 


_Original Data Base_

<img width="1003" alt="ths_original_scores" src="https://user-images.githubusercontent.com/107893200/181681586-cab2901f-9d10-4266-ad92-f0615afb1f0d.png">

_Updated Data Base_

<img width="795" alt="ths_updated_scores" src="https://user-images.githubusercontent.com/107893200/181681629-685d4c64-f687-4fc2-b43e-297876ddcc6c.png">


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

1. d
2. d
3. d
4. d
