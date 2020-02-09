## DSI Project 1: SAT and ACT Analysis
By: Yeo Jia Chi

## Problem Statement
The Scholastic Assessment Test (SAT) and the American College Testing (ACT) are two widely used standardized testing methods for college admissions in the United States. As members of the College Board, our organization has been responsible for the development and administration of the SAT since its inception in 1926.

In an effort to more closely align the SAT to reflect the problems encountered by high-school students during class, our SAT has undergone several changes in 2016 to help meet these goals. Furthermore, to improve student participation and combat perceived advantages in expensive SAT Test Preparation, the College Board has also partnered with the Khan Academy to provide free online SAT practice problems and video classes.

Therefore, in order to expand the reach of SAT in US high-schools, our team has been tasked to study and propose 1 US state for the College Board to target SAT promotion efforts. Using the SAT 2017/18 and ACT 2017/18 as initial data, any potential leads should be further investigated using external data. Finally, our findings and recommendations should be presented to the College Board in a non-technical setting.

## Executive Summary
Contents:
- 2017 Data Import and Cleaning
- 2018 Data Import and Cleaning
- Exploratory Data Analysis
- Data Visualization
- Descriptive and Inferential Statistics
- Outside Research
- Conclusions and Recommendations

## Data Dictionary
|Feature|Type|Dataset|Description|
|:-------|---|---|---|
|**state**|object|ACT/SAT|State name within the USA|
|**sat_part_2017**|int64|SAT|State SAT participation rate (%) in 2017|
|**sat_ebwr_2017**|int64|SAT|State average SAT EBRW score in 2017|
|**sat_math_2017**|int64|SAT|State average SAT Math score in 2017|
|**sat_total_2017**|int64|SAT|State average SAT Total score in 2017|
|**act_part_2017**|int64|ACT|State ACT participation rate (%) in 2017|
|**act_eng_2017**|float64|ACT|State average ACT English score in 2017|
|**act_math_2017**|float64|ACT|State average ACT Math score in 2017|
|**act_read_2017**|float64|ACT|State average ACT Reading score in 2017|
|**act_sci_2017**|float64|ACT|State average ACT Science score in 2017|
|**act_comp_2017**|float64|ACT|State average ACT Composite score in 2017|
|**sat_part_2018**|int64|SAT|State SAT participation rate (%) in 2018|
|**sat_ebwr_2018**|int64|SAT|State average SAT EBRW score in 2018|
|**sat_math_2018**|int64|SAT|State average SAT Math score in 2018|
|**sat_total_2018**|int64|SAT|State average SAT Total score in 2018|
|**act_part_2018**|int64|ACT|State ACT participation rate (%) in 2018|
|**act_comp_2018**|float64|ACT|State average ACT Composite score in 2018|

## Conclusions and Recommendations
### Key Findings

It is proposed that the College Board increase their efforts in targeting high-school students in the **state of California**.
- This is due to their large population of annually graduating high-school students, of which lies a sizable 100-150 thousand students (~40%) that have yet to take the SAT.
- A small percentage increase in SAT participation from California would have a huge numerical increase in student participation number. This is as opposed to lower density US states with much fewer student numbers.
- From a growth projection point of view, it also logical given that California be chosen given that this large student body population is expected to remain the largest in US for the the coming decade.

### Recommendations

To fully develop a comprehensive strategy, we propose additional studies in the state of California to determine the underlying issues affecting SAT participation. A three-pronged approach is as follows:

1) **California State Education Policy:**
	- What are the schemes in place to help high-school students explore college opportunities and their application rates?
	- Are there sufficient state-sponsored college scholarships or tuition grants? And do students utilize such resources?
	- Is there sufficient demand/need to justify implementing mandatory SAT tests for all students?

2) **High-school Student Background**:
	- How is the receptivity of California High School students towards college education or seeking employment?
	- How do their family backgrounds affect their choices to either work, or attend college?
	- Are they receptive towards taking an SAT test?
	- Do they believe that taking the SAT will help improve their chances to getting into college?

3) **College Admission Policy**:
	- How do California state colleges rank potential students for admission?
	- How much does the SAT score impact the student's chances of entering college?
	- What are the schemes in place to help disadvantage students to attend college?
