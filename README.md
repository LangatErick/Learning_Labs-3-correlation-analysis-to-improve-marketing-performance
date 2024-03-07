# Learning_Labs-3-correlation-analysis-to-improve-marketing-performance
![image](https://github.com/LangatErick/Learning_Labs-3-correlation-analysis-to-improve-marketing-performance/assets/124883947/333a7861-eb89-452c-8761-477f08530b2b)
## How to use correlation analysis to improve marketing performance in  R Programming

### Why correlation?
It is important to understand what drives relationships. For example, if you want to determine how marketing performance impacts your sales numbers, you must account for all factors that can explain your sales numbers. This could include factors like:

- marketing channels
- season
- geographic location
etc.
Correlation is a great exploratory tool that can sometimes reveal interesting patterns in your data. Most importantly, once you get the hang of it, it is straightforward to add to your analysis toolkit.

### What is correlation?
![image](https://github.com/LangatErick/Learning_Labs-3-correlation-analysis-to-improve-marketing-performance/assets/124883947/9522975d-dcb8-404d-a18b-8a1f46b90227)
A correlation is a statistic that quantifies the strength between 2 variables. The statistic is called the correlation coefficient denoted as r.

The correlation coefficient or r is a number between +1 and -1 and is calculated to represent the linear relationship between two variables. An r close to 1 indicates a strong relationship between the variables while an r close to 0 indicates a weak relationship.

## How to interpret the correlation
Correlation thresholds using Jacob Cohen’s Rule of Thumb which is often used in the behavioral sciences to interpret the effect size:

- r >= 0.5 large or strong association
- r = 0.3 medium association
- r = 0.1 small or weak association

If the underlying data distribution is not normal, then you could transform (e.g. logarithm, Box-Cox, etc.) your variables before attempting to apply these thresholds.

### What’s an acceptable correlation?
Even if the correlation coefficient is at or near zero, that doesn’t mean no relationship exists. It’s just that the relationship isn’t linear, but there could be other relationships which is why it’s important to visualize your variables beforehand.

## Exploratory Visualization and Correlation Analysis
We will be using this marketing dataset.
![image](https://github.com/LangatErick/Learning_Labs-3-correlation-analysis-to-improve-marketing-performance/assets/124883947/134c592b-7b8a-4fd7-994a-269b8d1c4eb1)

![image](https://github.com/LangatErick/Learning_Labs-3-correlation-analysis-to-improve-marketing-performance/assets/124883947/68311b20-ebaa-4a95-b430-609cd27206fb)

