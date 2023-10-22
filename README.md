# Data-Analytics
Jupyter Notebook 

## Purchases Dataset
### Abstract:

In our recent exploration, we delved into the realms of consumer habits and educational performance using Python-based data analysis. Our project tackled several facets of these domains, providing insights and shedding light on intriguing patterns.

### Consumer Habits:

Item Pricing Analysis: We initiated our inquiry by constructing a dictionary of consumer items and their prices. By converting this dictionary into a pandas series, we offered a structured look into the costs of common items. This serves as a foundational step for future studies that may wish to delve deeper into pricing trends and consumer purchasing behaviors.
Numerical Operations and Visualizations:

Matrix Operations: Our project illustrated the ease and power of numpy by performing a series of array operations, including addition, multiplication, reshaping, and slicing. Such numerical manipulations hold significance in various fields, from computer graphics to physics simulations.

Visual Narratives: A highlight of our exploration was the creation of multiple subplots using matplotlib. These plots, showcasing the relationships between an array and its powers, serve as a testament to the versatility of Python in data visualization.

### Educational Performance Insights:

Correlational Analysis: We turned our focus to a dataset of students, aiming to discern patterns and relationships. By computing the Pearson correlation coefficient, we ascertained the linear relationship between students' age and weight.

Visualization and Interpretation: Seaborn, a potent visualization tool, was employed to create pairplots, pie charts, and heatmaps of the student data. These visualizations were pivotal in understanding grade distributions, participation impacts, and the relationship between different academic parameters. Key findings included the moderate positive correlations between various exams and the intriguing observation that class participation might not be a strong predictor of exam performance.

Statistical Overview: Finally, our project dabbled in statistical measures, computing the mean and standard deviation of ACT scores. This elementary analysis underlines the importance of statistical tools in understanding and interpreting datasets.

### Conclusion:

Our project encapsulates the power and versatility of Python in data analysis. Through a mix of numerical operations, visualizations, and statistical measures, we've painted a holistic picture of consumer habits and educational performance. This exploration paves the way for deeper inquiries, urging us to ask more complex questions and seek nuanced answers in the vast realm of data analytics.




## Salaries Exercise
From the analysis, we can gain insights such as the distribution of salaries across different job titles, trends in average base pay over the years, the prevalence of certain job titles, and more. This information can be beneficial for benchmarking, policy-making, and understanding compensation structures in the San Francisco Fire Department.


## Seaborn Visualization Exercises

In this exercise, we delve into visualizations using Seaborn, a powerful Python visualization library. We work with several datasets, primarily focusing on the "Salaries" and "Iris" datasets.

### Dataset Overview:

- **Salaries Dataset**: Contains information about various employees, their job titles, and different pay components.

- **Iris Dataset**: Commonly used in pattern recognition, it contains measurements for 150 iris flowers from three different species.

### Visualizations:

1. **Distribution Plot for Total Pay (Salaries Dataset)**: 
    - Used the `distplot()` function. Note: `distplot` is deprecated and is expected to be removed in Seaborn v0.14.0. 
    - Showcases the distribution of the Total Pay for the employees.
    - Handled NaN values using the `dropna()` function.

2. **Pair Plot (Iris Dataset)**: 
    - Provides a pairwise relationship in a dataset. 
    - By using pair plots, we can immediately see the distributions of single variables and relationships between two variables.

3. **Boxplot (Iris Dataset)**: 
    - A graphic way to display the distribution of data based on a five-number summary (minimum, first quartile, median, third quartile, and maximum). 
    - In this exercise, we created a horizontal box plot for each feature in the Iris dataset, offering insights into the variability of each feature and potential outliers.

4. **Comparison of Pair Plots with Different Diagonal Plots (Iris Dataset)**:
    - Demonstrates the difference in using scatter plots versus histograms in the diagonal of pair plots.
    - This helps in understanding the distribution of individual variables in the dataset.

5. **Categorical Plot (Titanic Dataset)**:
    - We used the `countplot()` function to visualize the distribution of passengers by gender in the Titanic dataset. This gives insights into the gender distribution of passengers aboard the Titanic.
