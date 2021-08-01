## School District Analysis

The purpose of this analysis was to provide the District Board with a high-level snapshot of the district's key metrics:

* Total number of students
* Total number of schools
* Total budget
* Average math score
* Average reading score
* Percentage of students who passed math
* Percentage of students who passed reading
* Overall passing percentage

In addition to these district level metrics, analyses were also provided at the school level in order to get a better picture of student performance at each school in the district as well as school budgets and spending per capita.

# Results

* District Summary changes
At the district level, the changes to math and reading as a result of censoring the test results of 9th grade students at Thomas High School was small. See below for the District Summaries before and after data cleaning.

Initial District Summary
------------------------
![Module District Summary](https://user-images.githubusercontent.com/86337475/127750898-ec6ce302-fcbe-40cf-b7ed-6aca15550f7b.PNG)

District Summary after data cleaning
------------------------------------
![Challenge District Summary](https://user-images.githubusercontent.com/86337475/127750913-3597014f-7782-45e3-8dbd-0ebba99f902c.PNG)

After removing compromised test results from Grade 9 at Thomas High School:
* Average Math Score dropped 0.1%
* Average Reading Score did not change (due to rounding of the values)
* % Passing Math dropped 0.2%
* % Passing Reading dropped 0.3%
* % Overall Passing dropped 0.1%

# School Summary Changes
-------------------------
Since the only school in the district to have their data changed was Thomas High School, no other school saw changes in math and reading.  

* Thomas High School Changes
* Average Math Score dropped 0.7%
* Average Reading Score dropped 0.5%
* % Passing Math dropped 0.8%
* % Passing Reading dropped 0.3%
* % Overall Passing dropped 0.3%

![HEADER](https://user-images.githubusercontent.com/86337475/127754022-b3c6cd05-ddd2-41e5-9e2b-def9a059f3ee.png)
![Thomas_Before](https://user-images.githubusercontent.com/86337475/127754036-604c7d79-139e-4a53-932a-bfacac66eb8f.PNG)
![thomas_after](https://user-images.githubusercontent.com/86337475/127754092-c56f92c6-8b85-4243-9441-0c12bc622450.PNG)

Math scores by grade
--------------------------------
**Before Cleaning**
![before_math](https://user-images.githubusercontent.com/86337475/127754833-146ceb1a-b118-4e70-9d56-159468b1968d.PNG)


**After Cleaning**
![after_math scores by grade](https://user-images.githubusercontent.com/86337475/127754763-b94bd4ea-2e90-4aab-a1d1-310d6eb52010.PNG)

Reading Scores by grade
-----------------------
**Before Cleaning**
![reading_before](https://user-images.githubusercontent.com/86337475/127754855-904a17da-f46b-44aa-b90d-6a7c453e82c0.PNG)

**After Cleaning**
![reading_before](https://user-images.githubusercontent.com/86337475/127754784-2bab9af2-8a27-4d5a-9c79-7b99b7d972b5.PNG)

Scores by school spending
-------------------------
**Before**
![spending_before](https://user-images.githubusercontent.com/86337475/127754890-518aee8e-1583-4094-a53e-669624b9eaf4.PNG)


**After**
![spending_after](https://user-images.githubusercontent.com/86337475/127754894-b4a61d00-a34d-4443-9930-823a1618d898.PNG)


Scores by school size
----------------------
**Before**
![size befre](https://user-images.githubusercontent.com/86337475/127754943-fd0bfe97-697b-4c64-a01b-27db0faba044.PNG)

**After**
![size_after](https://user-images.githubusercontent.com/86337475/127754949-3bc82989-da6d-4557-a38b-5b762381d72d.PNG)

Scores by school type
---------------------
**Before**
![type_before](https://user-images.githubusercontent.com/86337475/127755007-e2d3f532-5e50-42c0-bd61-c3fabdfd9dfb.PNG)

**After**
![type_after](https://user-images.githubusercontent.com/86337475/127755012-48606b2f-a97e-418d-88c6-140ed3d50376.PNG)

# Summary
In summary, replacing the math and reading scores for Grade 9 at Thomas High School with NaNs had a slight negative impact on district summary metrics:
* Average Math Score dropped 0.1%
* Average Reading Score did not change (due to rounding of the values)
* % Passing Math dropped 0.2%
* % Passing Reading dropped 0.3%
* % Overall Passing dropped 0.1%

Charter school types were slightly negatively impacted, as Thomas High is a charter school.

