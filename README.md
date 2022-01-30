#School District Analysis

##Purpose of School District Analysis

The school board has notified Maria and her supervisor, to whom are both expert data scientists within the school district, to make the appropriate adjustments to their data file "students_complete.csv" after learning that there were evidence of academic dishonesty with the reading and math scores for Thomas HIgh school ninth graders. In order to make the appropriate adjustments, we replaced ninth grade math and reading scores for Thomas High school with NaNs and ran new numbers and tables for the school district analysis. This analysis helps the school board to get a snapshot of the district's key metrics and make informed decisions on where money has been spent and what schools may need more funding in order to improve reading and math performance. 

##Results: Using bulleted lists and images of DataFrames as support, address the following questions.

### District Summary

After having removed ninth graders from Thomas High School, the new total student count is 38,709 students, as opposed to the original student count of 39,170 students in the district. 

Original District Summary
![Original District Summary](https://user-images.githubusercontent.com/96089187/151690147-9e80252f-a46b-42cf-8e0d-bf888a9acf46.png)

New District Summary
![New District Summary](https://user-images.githubusercontent.com/96089187/151690167-9101e129-d163-43e7-ba4b-eaaa4d05164b.png)

* Average Math Score: The original (PyCitySchools) average math score was 79.0, whereas the new (PyCitySchool_Challenge) average math score is 78.9, which is only a difference of 0.1.
* Average Reading Score: Stayed the same at 81.9
* Passing Math Percentage: The original passing math percentage was 75%, whereas the new passing math percentage is 74.8%. Thus, due to the adjustment in Thomas High School data, the passing math percentage decreased by 0.2%. 
* Passing Reading Percentage: The original passing reading percentage was 86%, whereas the new passing reading percentage is 85.7%, which is a 0.3% decline due to the Thomas High School data needing to be adjusted. 
* Overall Passing Percentage: The Overall passing percetage decreased by 0.1%. 

Overall, the Thomas High School data adjustment has slightly decreased the score and passing percentages of the district's overall data. 

### School summary

Thomas High School was originally the top two schools. However, with the adjustment, Thomas High School is not even in the top five. Because the data has been adjusted with Thomas High School, Thomas High School is the only school whose values/data have changed. 

Orginal Thomas School Summary - Top Two Schools
![Original THS school summary](https://user-images.githubusercontent.com/96089187/151690574-965367f4-8fc5-4e52-b5d4-5349172bf48c.png)

New Thomas School Summary
![New THS school summary](https://user-images.githubusercontent.com/96089187/151690581-7e724c00-640e-4b65-9800-f26f4d9ea030.png)

* The most drastic shift is the Overall Passing Percentage with Thomas High School. Originally, Thomas High School's Overall Passing Percentage was 90.9%. With the adjustments, the Overall Passing Percentage has decreased to 65.1%. 

### Replacing the ninth graders’ math and reading scores affected Thomas High School’s performance

As previously mentioned, Thomas High School, with the ninth grade scores, was ranked top two. However, with the removal of the ninth grade scores, Thomas High School's rank has fallen as well as the Overall Passing Percentage - from 90.9% to 65.1%. 

### Replacing the ninth-grade scores affect the following:

* Math and reading scores by grade: Thomas High School's ninth grade class no math and reading scores since it has been changed to NaN. Whereas other math and reading scores remained the same, including tenth, eleventh, and twelth grade math and reading scores for Thomas High School. 

* Scores by school spending: Below, you will see the original and new scores by school spending. The most drastic change is in the $630-644 bin, where Thomas High School falls under, with a decrease in passing math, reading, and overal all percentages. While the percentages decreased, the average score for math and reading stayed the same. 

Orignal Scores by School Spending
![Original Scores by School Spending](https://user-images.githubusercontent.com/96089187/151690879-6154321c-ba57-4857-b9bc-527f5a67f53e.png)

New Scores by School Spending
![New Scores by School Spending](https://user-images.githubusercontent.com/96089187/151690876-6f33c924-e50f-4e9b-aa0e-eb23618ea14d.png)

* Scores by school size: The Medium school size bin (1000-2000) saw a decrease in passing math, reading, and overall percentages. This is not a surprise, as Thomas High School is a medium school size. The percentages decreased in math from 94% to 93%, in reading from 97% to 91% and overall from 91% to 85%. 

Original Scores by School Size
![Original Scores by School Size](https://user-images.githubusercontent.com/96089187/151691045-4a8cbcaa-5855-4274-aa1c-1ca49139e022.png)

New Scores by School Size
![New Scores by School Size](https://user-images.githubusercontent.com/96089187/151691055-4258369b-604b-4d89-a34b-78ea32b7fb7f.png)

* Scores by school type: Thomas High School is a Charter School and thus we see a decrease in the math, reading, and overall passing percentages with the Charter Schools. 

Original Scores by School Type
![Original Scores by Type](https://user-images.githubusercontent.com/96089187/151691217-191a4de1-bd20-4fe7-a81d-acc27067b00b.png)

New Scores by School Type
![New Scores by Type](https://user-images.githubusercontent.com/96089187/151691226-77f50cfb-8ab0-4807-8f0a-383dde5e2c2e.png)

##Summary: 

* Within the district, Thomas High School was originally ranked #2. With the omission of the ninth grade math and reading scores, they fell in the ranks. Thomas High School experienced a decrease in math, reading, and overall percentages. 
* Within the Thomas High School, their most drastic shift is the Overall Passing Percentage where the original Overall Passing Percentage was 90.9% and decreased to 65.1% passing. 
* There are decreases in the medium school size performance and in charter school performances due to the data adjustments with Thomas High School. 
* The biggest surprise is that much of the average math and reading scores were not impacted. 
