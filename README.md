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

Almost all of the scores dropped, aside from the average reading score, which rose by 0.05 points. The overall passing percentage saw the biggest change, reducing by 0.3%.


