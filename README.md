# ESDS_Final
Description
This project analyzes data related to seed count in kangaroo rat mound locations and seed count in relation to plot type, plant species, and total number of inflorescences. The analysis aims to explore potential differences and relationships between these variables.

Installation
To run the code in this project, you need to have the following dependencies installed:


R packages: here, dplyr, janitor, ggplot2, tidyverse, naniar, skimr, GGally, flextable, car
Usage
Clone the repository to your local machine.
Open the R script file.
Set the working directory to the cloned repository.
Install the required R packages if not already installed.
Run the code in your preferred R environment.
Data
The project uses the following datasets:

sev208_kratseedbank_20120213.csv: Contains data on seed count in kangaroo rat mound locations.
shrubstudy_community_flower_counts.ms.data.csv: Contains data on seed count, plot type, and total number of inflorescences.
shrubstudy_individual_flower_counts.ms.data.csv: Contains data on seed count and plant species.
shrubstudy_pollinator.ms.data.csv: Contains data on seed count and plant species.
Make sure to place the datasets in the appropriate data folder within the project directory.

Analysis
Kangaroo Rat Mound Locations
The code reads the sev208_kratseedbank_20120213.csv dataset.
It performs data cleaning and transformation.
A histogram is created to visualize the distribution of seed count.
Levene's test is conducted to check the homogeneity of variances across mound locations.
An ANOVA model is created to analyze the difference in seed count between mound locations.
The results of the analysis are presented.
Seed Count and Other Variables
The code reads the relevant datasets (shrubstudy_community_flower_counts.ms.data.csv, shrubstudy_individual_flower_counts.ms.data.csv, shrubstudy_pollinator.ms.data.csv).
Data cleaning and filtering are performed.
Histograms are created to examine the distributions of total number of inflorescences and seed count.
Levene's test is conducted to assess the homogeneity of variances.
A multiple linear regression model is built to analyze the relationship between seed count, plot type, plant species, and total number of inflorescences.
Various plots are generated to visualize the data and model results.
The findings and conclusions of the analysis are summarized.
Results
The analysis provides insights into the differences in seed count between kangaroo rat mound locations and the relationships between seed count, plot type, plant species, and total number of inflorescences. Key findings include:

Significant differences in seed count between kangaroo rat mound locations.
Marginally significant difference in seed count between shrub and open plots.
No significant differences in seed count among different plant species.
Highly significant positive relationship between the total number of inflorescences and seed count.
Contributors
Jacob Coggshall