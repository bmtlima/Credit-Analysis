# Credit-Analysis

Submission for Duke Quantitative Finance Club

Overview:

1. Parsing Data: 
    I first created a new file called data.txt without the text explaining the data, then I created a smaller version of data.txt called small.txt. Working with small.txt, the data was more manageable, and after parsing it I just had to expand the logic for data.txt

2. Analizing Data:
    2.1 Categorical Variables:
        Aside from creating plots with the approval rate for each variable, I also tested two hypothesis regarding the correlation between unemployment, marriage, and gender. 
    2.2 I created visualizations and a heatmap for all of the variables

3. Build Predictive Model:
    3.1 Pre-Processing:
        After getting the log of the account variable in order to decrease its skewness, I converted all of the data into numbers ranging from 0 - 7, which is ideal for the machine learning models. Additionally, I dropped out the age and amount variables from the analysis, as step 2 showed they weren't particularly relevant. 
    3.2 Modelling:
        I applied 9 ML models to the data, and analyzed their means and standard deviations. From this, the best model was Support Vector Machines. 