# School_District_Analysis
Using Pandas in Jupyter Notebooks to remove compromised data from Thomas High School 9th graders and run district wide data analysis to deliver to the school board.
## Results
- After cleaning the data of any compromised test scores, the district summary was impacted in the following ways:
    - "% Passing Math" decreased from 75% to 74.8%.
    - "% Passing Reading" decreased from 86% to 85.7%
    - "% Overall Passing" decreased from 65% to 64.9%
- We then looked at the per school summary:
    - Thomas High School was the #2 school in terms of "% Overall Passing" both before and after eliminating the compromised 9th grade data.
    - "% Passing Math" deacreased from 93.27% to 93.19%
    - "% Passing Reading" decreased from 97.31% 97.01%
    - "% Overall Passing" decreased from 90.94% to 90.63%
- While removing the 9th graders did lower the scores to which math and reading may not be in the same position they were initailly, it seems like overall the school still remains in the "2nd" position in terms of overall test performance.
- Math and Reading scores ranked by grade would show no change in this category for 10th - 12th grade as we are looking at these scores independent from other grades around them
- When comparing scores by spending per student, I don't beleive I have an accurate analysis on that. My dataframe that is comparing those figures is ommitting the 9th grade class in terms of spending, making it look like the enirety of the budget was spent on 10th-12th.
- Thomas High School is classified in this analysis as a "Medium High School". The removal of the 9th grade class resulted as follows:
    - "% Passing Math" remained at 94%
    - "% Pasing Reading" remained at 97%
    - "% Overall Passing" remained at 91%
## Summary
After the removal of the 9th grade class at Thomas High School, we can draw a few conclusions. It does appear that the compromised test scores were impacting the overall performace of the school as a whole, but only to a minute degree. The 10th-12th grade students still performed near the top across all categories amongst their peers. It does appear that both school size and school type have the greatest correlation to predicting student success. Both medium and small schools as well as charter schools performed well above their large, district peers. It does appear that the only medium and small schools in the district were charter schools.
