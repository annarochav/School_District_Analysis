# 🚀 School_District_Analysis.
Challenge Week4 Data Analysis BootCamp using Python/ Jupyter Lab / Pandas / Numpy
## ⚡Overview of the school district analysis: 
Assist Maria the Data Scientist for a city school district, with cleaning and analyzing data of student test scores and founding. The analysis will provide an insight on how well students are performing in math and reading in comparison with their budgets. Ongoing data analysis will help student success.
The scores for the 9th graders at Thomas High School were removed because data was altered. In this summary we will compare the before and after this change and how it affected the results.
## ⚡Results:
**How is the district summary affected?**

If we compare the initial district summary with the updated one, we can see that there’s a decrease of 0.1% in the average math score, a decrease of 0.2% in the passing math percentage, a decrease of 0.3% in the passing reading percentage and finally a decrease of 0.1% in the overall percentage.

<img src="https://github.com/annarochav/School_District_Analysis/blob/main/Resources/district_summary.png" width="800" height="100" /> 

**How is the school summary affected?**

The scores of Thomas High School were the only ones affected. The initial passing math percentage was 93.27% and it dropped to 66.91%, the passing reading percentage was 97.30% and dropped to 69.66%, the overall passing percentage was 90.94% and dropped to 65.07%. 

<img src="https://github.com/annarochav/School_District_Analysis/blob/main/Resources/school_summary.png" width="550" height="550" />

**How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

In the initial analysis, Thomas High School was in the top school performers with an overall passing percentage of 90.94%. In the updated analysis, Thomas High School became one of the bottom school performers with a 65.07% of overall passing, that's why it's better to remove 9th graders scores and make the analysis with the rest of the school grades (10th, 11th, and 12th). With this strategy, the change is not significant and Thomas High School would remain in the top school performers.

<img src="Resources/ninth_graders_math_and_reading_scores.png" width="600" height="300" />
