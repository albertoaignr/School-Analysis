# School Analysis 

Data collection for this challenge, started by reading the CSV file where all the information for the schools will be taken from. This reading of the file followed by cleaning the data from missing values '.dropna()' and duplicates '.drop_duplicates()', will be our starting point for the analysis.

Drilling down into the data, there are some values that could be grouped and sorted for display that could give a better understanding for an analysis. 

## Results

From the analysis on the data, made by grouping and sorting values for school types, it can be seen:

- The average School budget is greater for Public schools than Charter schools.
- Charter Schools performed better when comparing to Public Schools in overall Math scores.
- As the distribution of population is different for any school, data from the higher count of students takes more weight for any evaluation.

#### Adittional considerations:
- It could be done an analysis of student count vs school type, school name and grades for a deeper understanding on the weight of the data, as it can highlight which group is affecting the scores and maybe find a way to improve the outcomes for any topic.
- Comparing average reading scores and math scores, might serve as a tool to determine which area of school could benefit from improvement.
