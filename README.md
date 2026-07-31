# MIS-311
Student Performance Data Analysis using Microsoft Excel.
1.Data overview

Dataset Description

Dataset: Student Performance Dataset
Source: Kaggle (Student Performance Dataset)
Number of rows and columns: [200,8] 
Background: Student Performance dataset consists of data regarding the academic performance of students. The dataset comprises information on demographic variables, parental level of education, and performance of students in mathematics, reading, and writing.

2. DATA CLEANING
   
2.1 Missing Values
Missing values were identified in the parental_level_of_education column. These missing values were replaced with the most frequent category associate's degree to preserve the dataset and avoid losing observations.

2.2 Duplicate Rows
Duplicate rows were identified and removed to improve data quality before analysis.

3.DESCRIPTIVE STATISTICS

3.1 Descriptive Statistics
![Descriptive Statistics](descriptive%20statistics.png)


Mean values for all three variables are 64.18, 67.61, and 66.33. These values show similar results, meaning that the performance level was quite similar. The maximum value of the mean is 67.61, and the minimum one is 64.18; hence, there is not much difference between these values. Standard deviation values vary from 15.82 to 16.29, which means that the variability level is quite equal among all three variables.

All three variables demonstrate negative skewness -0.36, -0.23, and -0.33. It shows that the distributions are slightly skewed to the left, meaning that some low values affect the mean negatively. However, the first variable has a larger kurtosis 0.93 than the other two -0.15 and 0.06. Hence, its distribution is slightly more peaked than others and has more extreme values. There are 198 observations for each variable; hence, the sample size is the same.

Combined data show that the mean value is 66.04 and the median value is 66.33. As these numbers are very close, it can be said that the distribution is balanced.

3.2 Visualization
![Average Score by Parental Level of Education](average%20of%20parental%20scores.png)


Chart 1: Average Score by Parental Level of Education
Students whose parents have some high school education recorded the lowest average score 60.46, while those whose parents completed high school averaged 62.29. This indicates that students from families with lower parental education levels may benefit from additional academic support.
![Distribution of Average Scores](distribution%20average%20scores.png)
Chart 2:Distribution of Average Scores
The most prevalent score range is between 64.2 and 73.4. The majority of students got scores within the range of 55 to 82.6, and therefore there was generally acceptable performance by the students. Few students got extremely low (below 45.8) and extremely high (above 91.8) average scores. There is slight left skewness in the distribution, implying a small proportion of lower scores. Generally, the distribution of scores is not widely dispersed and is therefore relatively consistent among students.

=>It can be observed from the histogram that the score distribution of the majority of students is concentrated in the middle score range, which means that there was average performance among the students. Few students had very low or high scores.
