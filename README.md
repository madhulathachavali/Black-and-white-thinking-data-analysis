# Black-and-white-thinking-data-analysis

Black and white thinking is characterized by thinking in absolutes. For instance, one thinks he/she is either too good or too bad at something. This is an important variable in the assessment of many psychological disorders.

The project aims to determine if there is a relationship between higher levels of black and white thinking, and higher levels of self-reported cases of depression. To understand the data further, K means clustering is used to form clusters and individual clusters are analyzed for simplicity, fatalism, and depression.

The dataset used in this analysis is the Ginzberg data frame, which pertains to patients with psychiatric hospitalization due to depression. This dataset is sourced from the book "Applied Regression Analysis and Generalized Linear Models, Second Edition" by J. Fox (2008).

## This study measures black and white thinking using three variables :

1. Simplicity or black and white thinking

2. Fatalism

3. Depression

## Conclusion

Discrete groups were created using k=3 with minimal overlapping among the groups. Group 1 has higher simplicity levels, which correlates with higher depression and fatalism levels. Similarly, Group 0 and Group 2 have moderate and lower simplicity thinking respectively, which correlates with moderate and lower depression levels.

Groups 0 and 1 showed a strong correlation between simplicity, fatalism, and depression. Group 2 showed lower simplicity but higher fatalism. This group is an exception to the correlation between depression and fatalism as well. Further understanding of this group to required to know what is causing fatalism.

In conclusion, there is a linear and strong positive relationship between black and white thinking and depression using the whole dataset. K-means clustering helped in identifying two classes of the population. Majority class (groups 0 and 1) strongly correlated with simplicity, depression, and fatalism. Minority class (group 2), even though they experience fatalism, it does not correlate with simplicity and depression. Without cluster analysis, this class may be mistakenly confined to the majority class.
