# School District Analysis Using Pandas
## Project Purpose and Overview
A school board detected academic dishonesty in their ninth grade math and reading scores, though they are unsure as to the full extent. An analysis comparing the same metrics across the entire school district was performed just before this discovery. As a result, they have requested that the 9th grade scores from Thomas High School, the school in question, be removed. This analysis will compare the old district summary to the new, up to date version.
## Results
The school district has a total of 39,170 students across 15 different school. Thomas High School has a total of 1,635 students, 461 of which are in the 9th grade. To account for dropping 461 tests, the percentages for district scores were calculated using 38,709 as the denominator. Otherwise, the total student count remained the same. Thomas High School math and reading scores ignored the 9th grade entirely.

The following metrics used to analyze the data were:
  - District summary
  - Individual school performance
  - Ranking best to worst performing schools
  - Math and reading scores by grade
  - Student scores by school spending per capita
  - Student scores by school size
  - Student scores by school type

Note: Thomas High School will be a part of the group highlighted blue in all of the following photos. Also, the scores per grade in each individual school was left out of the results, as it was untouched everywhere but Thomas High School, where the 9th grade simply was left void.

### District Analysis

**Original District Summary**

![DistrictSummaryOrig](https://user-images.githubusercontent.com/92493572/142491270-36cb6d41-eb74-4c58-ad6e-1371ecbe3a69.png)

**Updated District Summary**

![DistrictSummaryUpdate](https://user-images.githubusercontent.com/92493572/142491276-89902924-fd50-4692-b242-bcd5bdfcfbf5.png)

Considering the format, the updated figure shows that:
  - averages math scores dropped by 0.1%
  - passing math dropped by 0.2%
  - passing reading dropped by 0.1%
  - percent overall passing dropped by 0.3%

### Individual School Performance
Thomas High School, highlighted below in blue, is the only focus in this analysis because individual school data was not modified.

**Original School Performance**

![School_Perform_Orig](https://user-images.githubusercontent.com/92493572/142500261-27239bf5-5daf-4dde-9cc5-beb2404f1fb7.png)

**Updated School Performance**

![School_Perform_Updated](https://user-images.githubusercontent.com/92493572/142500670-fe518560-b08e-475b-8741-2fbb684a9c61.png)

Almost all the scores dropped, aside from the average reading score, which rose by 0.05 points. The overall passing percentage saw the biggest change, reducing by 0.3%.

### Student Scores by Spending Per Capita

**Original Student Scores by Spending Per Capita**

![School_Spend_Orig](https://user-images.githubusercontent.com/92493572/142502948-f8261126-b4d6-43bb-902d-26fbe9493fb7.png)

**Updated Student Scores by Spending Per Capita**

![School_Spend_Updated](https://user-images.githubusercontent.com/92493572/142502962-e674598d-f406-4252-bf14-609cd0b18e48.png)

Although the scores changed by fractions of a percent, they did not change enough to affect the rounding process for the above calculations.

### Student Performance Based on School Size

**Original Student Scores by School Size**

![School_Size_Orig](https://user-images.githubusercontent.com/92493572/142503638-30e3aea9-fa37-4c41-8a57-225c97e1c7ad.png)

**Updated Student Scores by School Size**

![School_Size_Updated](https://user-images.githubusercontent.com/92493572/142503673-98157e50-cf25-466b-ab5b-b35b0bee44e1.png)

The same result is found in this case; there is no notable change, even to the first decimal place.

### Student Performance Based on School Type

**Original Student Scores by School Type**

![School_Type_Orig](https://user-images.githubusercontent.com/92493572/142503893-5e4ba099-fb53-4e9c-9a89-38fb4ab40658.png)

**Updated Student Scores by School Type**

![School_Type_Updated](https://user-images.githubusercontent.com/92493572/142503902-a9d368c2-47be-4937-8170-e45603b09359.png)

Again, there is no change in the rounding process due to such a minor effect of replacing Thomas High School 9th Grade scores.

## Summary

The modification of removing Thomas High School 9th Grade scores has proven to be insignificant to the overall results, as it, in many categories, is unable to affect a decimal in the tenths place. Nonetheless, district results fell by between 0.1% and 0.3% in the math, reading, and overall passing percentages. The Thomas High School scores were not replaced with lower grades, but were instead left out of the calculations in a way that accounted for their absence. This means that the 9th Grade scores were above average to a degree that they were still able to have an effect on the entire district's results. It not only had an impact on district results, but to Thomas High School's overall performance. Almost all of their average scores dropped, with the average reading score rising by 0.05, meaning the 9th graders outperformed 10th, 11th, and 12th graders - further supporting the school board's suspicion.
