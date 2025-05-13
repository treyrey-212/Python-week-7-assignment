# Python-week-7-assignment
Dataset Summary:
Rows: 1,599
Columns: 12
Target Variable: quality (ranges from 3 to 8; higher = better quality)
No missing values in the dataset, which is ideal for analysis.

Statistical Insights:
Using .describe(), we find:
Alcohol content ranges from about 8.4% to 14.9%.
Higher quality wines tend to have higher alcohol content on average.
Volatile acidity (a negative wine trait) tends to be lower in higher-quality wines.
Citric acid and sulphates show a mild increase with higher wine quality.

Visual Findings:

Bar Chart: Average Alcohol Content by Wine Quality
Shows a clear upward trend: wines with higher quality scores tend to have higher alcohol content.
For example, average alcohol in wines rated 8 is higher than those rated 5 or 6.

Histogram: Alcohol Distribution
Alcohol content is slightly right-skewed, with a peak between 9.5% and 11.5%.
Fewer wines have very high alcohol content (>13%).

Scatter Plot: Alcohol vs. Residual Sugar
No strong correlation between alcohol and residual sugar.
Suggests that alcohol strength does not depend heavily on sugar level in these red wines.

Line Chart: Alcohol Trends Across Quality
The line chart reinforces the bar chart: higher wine quality is correlated with higher alcohol levels.


Overall Observations
Alcohol content appears to be a key indicator of higher wine quality in red wines.
Most features are numerical, making it suitable for regression or clustering tasks.
There is no clear linear relationship between residual sugar and wine quality.
The dataset is clean, with no missing values, and ready for machine learning or deeper statistical analysis.

