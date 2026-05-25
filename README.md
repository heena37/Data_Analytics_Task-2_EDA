### - PROJECT - 2 (Exploratory Data Analysis): Overview:
Conducted Exploratory Data Analysis and used the results to find trends, patterns and outliers in the data set.

# Tools Used:
- Python, Pandas, Matplotlib, Google Colab

# Analysis Performed:
Calculate the mean and median of a set of data.Calculate mean and median from data.
- Correlation analysis
- Outlier detection
- Trend analysis
  
# Dataset Information:

The data used for this project came from the data set provided during the internship program, and included transactional business-related data such as:
- Customer information
- Product details
- Payment methods
- Order status
- Sales values
- Pricing information

## Descriptive Statistics
Calculated important statistical measures such as:

- Mean
- Median
- Count
- Minimum value
- Maximum value
- Standard deviation

Used:
```python
df.describe()
```
##  Distribution Analysis:
Used histograms to analyze the distribution of the data in the column TotalPrice, and to gain insight into how the data is distributed across the sales.

### Histogram Analysis-
- Identified frequency distribution
Recognized data sets that are right-skewed.
Analyzed value concentration such as sales value, purchase value, etc.

## Outlier Detection-
Identified outliers by IQR (Interquartile Range) Method.
### IQR Formula Used
- Lower Bound = Q1 - 1.5 × IQR
- Upper Bound = Q3 + 1.5 × IQR
Data points outside the acceptable range were detected and analyzed.

## Correlation Analysis
Carried out correlation analysis of numerical variables to establish relationships and dependency.
Used:
```python
df.corr()
```
## Trend Analysis
Analyzed:
- Product performance
- Payment method usage
- Order distribution
- Revenue trends
Utilised aggregation and grouping to summarise findings.

# Visualizations Included
The project has the following visualizations:
- Histogram charts
- Outlier analysis
  
# Key Insights:
Analysis of the above observations, some of which are important:
Some products made a lot more money.
There was a positive skew in sales distribution.
A few extreme values were determined as outliers
Assessments of the most preferred payment methods showed different preferences among customers.
- Most of the transactions were within a moderate price range

The following approach is recommended for running the project:
## Step 1-
Open Google Colab
## Step 2-
Upload the data set file.
## Step 3-
Install necessary libraries if necessary
To install the packages, type pip install pandas matplotlib
## Step 4-
Execute the cells of the notebook one by one.

# Key Learning Outcomes:
In this project I learned:
The Exploratory Data Analysis techniques-
- Statistical analysis fundamentals
- Data visualization concepts
- Outlier detection methods
- Business insight generation
- Analytical thinking using Python
