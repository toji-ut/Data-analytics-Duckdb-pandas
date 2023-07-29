# Insurance Data Analysis with Python and DuckDB

This project conducts a comprehensive data analysis of an insurance dataset using Python and DuckDB. The main objective is to gain insights into various aspects of the insurance data, such as charges, regions, smoking habits, and other factors that might influence insurance costs.

## Dataset Overview
The analysis begins with loading the insurance data from a CSV file using Pandas. The dataset contains information about individuals, including their age, sex, BMI (Body Mass Index), number of children, smoking habits, region, and insurance charges.

## Data Exploration and Visualization
To explore the dataset visually, various data visualization libraries such as Seaborn and Matplotlib are utilized. The following analyses are performed:

1. **Barplots**: Visualize the relationship between different attributes, such as region, sex, and the number of children, against insurance charges. These bar plots provide a quick understanding of how these factors influence insurance costs.

2. **Linear Regression Plots**: Use scatterplots with linear regression lines to examine the correlation between age, BMI, and the number of children with insurance charges. Additionally, differentiate the data points by smoking status to explore any patterns related to smoking habits.

3. **Grouped Barplots**: Compare the mean insurance charges for the regions 'southwest' and 'southeast' using grouped barplots. This allows the identification of potential variations in charges between these regions.

4. **Pie Chart**: Analyze the distribution of smokers and non-smokers in the dataset by creating a pie chart that displays the proportion of smokers and non-smokers. Also, add the percentage and count for each category.

## Key Findings
The analysis reveals several key insights:

1. The region and sex of an individual appear to influence insurance charges. Different regions and genders show varying average insurance costs.

2. Smoking status has a significant impact on insurance charges. Smokers tend to have much higher insurance costs compared to non-smokers.

3. Age and BMI show a positive correlation with insurance charges. As age and BMI increase, insurance costs also tend to rise.

## Conclusion
The Python and DuckDB analysis provides valuable insights into the insurance dataset, allowing us to better understand the factors influencing insurance charges. The visualizations and statistical analyses facilitate a clear understanding of the relationships between different variables and insurance costs. This information can be useful for insurance companies in determining premium pricing strategies and identifying potential risk factors.

Feel free to explore the repository to gain a deeper understanding of the data analysis process and the insights obtained from the insurance dataset.
