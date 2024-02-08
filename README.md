# Data Preparation and Outlier Removal in R

## Introduction

This project demonstrates a comprehensive approach to preparing data and identifying outliers within a dataset using R. By utilizing the "uscrime.txt" data file, this project aims to clean the dataset for further analysis, with a focus on the "Crime" column which represents crimes committed per 100,000 people.

## Project Goals

The main objectives of this project include:
- To import and prepare the "uscrime.txt" data for analysis.
- To visually and statistically identify outliers within the data using plots, histograms, boxplots, and the Grubbs' test.
- To remove identified outliers and validate the cleaned data for use in further analysis.

## Methodology

The methodology employed in this project involves several key steps:
1. **Data Importation:** Loading the "uscrime.txt" file into R as a data table.
2. **Data Visualization:** Creating plots, histograms, and boxplots to visually inspect the data for potential outliers.
3. **Statistical Analysis:** Applying the Grubbs' test to statistically identify outliers within the "Crime" column.
4. **Outlier Removal:** Removing identified outliers from the dataset.
5. **Data Validation:** Re-assessing the cleaned data through visual and statistical methods to ensure readiness for further analysis.

## Results

The analysis began with visual and statistical examination of the "Crime" column, leading to the identification of significant outliers. Initially, an outlier with a value of 1993 was identified and removed. Subsequent analysis prompted the removal of another point, 1969, due to its deviation from the mean and standard deviation of the data.

After removing these outliers and re-analyzing the data, two more potential outliers were considered. However, a Grubbs' test resulted in a p-value of 0.1781, indicating that the probability of these points being outliers was not sufficiently low to justify their removal. The final dataset, with outliers removed, was deemed clean and suitable for further analysis.

This project highlights the importance of careful data preparation, the utility of visual and statistical methods for identifying outliers, and the decision-making process involved in data cleaning.
