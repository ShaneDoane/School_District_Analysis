# School_District_Analysis

## Overview
The purpose of this project was to use Python and its Pandas library to analyze math and reading scores within a school district. This published part of the project focused on replacing suspected dishonest scores for a subset of students at one school with null values, and the impact thereof.  There were 461 suspicious scores out of a total of over 39,000 records. All were 9th graders at Thomas High School. Results will be referring to before the replacement of suspicious scores with null values and after, unless otherwise noted.

## Results

### District Summary
* The removal of records had a minimal impact on the district summary (shown below)
* This is because only 461 of over 39,000 were removed.
![image](https://user-images.githubusercontent.com/93338132/150718198-b6b5d88a-e946-4466-89ee-d059f9edc37e.png)




### School Summary
* Thomas High School (THS) was the only school that had records removed.
* Impact of score removal shown below - result is a large improvement in scores in math and reading, with overall pass rates improving also.

Before
![image](https://user-images.githubusercontent.com/93338132/150718376-62d8a14b-f8ac-4615-a2d3-1f4daf339839.png)

After
![image](https://user-images.githubusercontent.com/93338132/150718484-3206495c-7b22-4c65-b7dd-ec84f3ccc91a.png)

* The result of the removal is an improvement in THS's relative standing with other schools, as grades 10-12 performed better than the removed scores from grade 9

### Scores by Groups

Math scores by Grade and School
![image](https://user-images.githubusercontent.com/93338132/150718958-4c196cea-0fd7-481b-80d5-d44703171141.png)
* Note THS has NaN values in 9th grade

Reading scores by Grade and School
![image](https://user-images.githubusercontent.com/93338132/150718987-3fb34d22-5c96-41f3-868d-1cca1718b2de.png)
* Note THS has NaN values in 9th grade

Scores by School Budget per Student
![image](https://user-images.githubusercontent.com/93338132/150719030-6f42a119-1bc7-43fd-8d15-6e6f66eea921.png)
* THS has a budget in the $630-644 range, so removing suspicious scores improved this group's averages

Scores by School Student Population
![image](https://user-images.githubusercontent.com/93338132/150719071-dacdd947-310a-49a9-b58b-26afb9c215f0.png)
* THS is a Medium (1000-2000) sized school, so removing suspicious scores improved this group's averages

Scores by School Type
![image](https://user-images.githubusercontent.com/93338132/150719635-b1557883-3729-47c6-a4a1-29fe7d9fe09b.png)
* THS is a Charter School, so removing suspicious scores improved this group's averages

### Summary
Removing suspicious scores had these effects:
* Improving THS overall reading and math scores
* Improving Medium-sized school pass rates
* Improving Charter School pass rates
* Improving Budget range $630-644 school's pass rates
