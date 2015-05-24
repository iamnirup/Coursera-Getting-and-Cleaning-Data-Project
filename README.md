# Coursera-Getting-and-Cleaning-Data-Project

This file describes the working run_analysis.R script.

* Set the working directory
* Make sure the folder "data" and the run_analysis.R script are both in the current working directory.
* Second, use source("run_analysis.R") command in RStudio. 
* Two output files are generated in the working directory:
  - merged_data.txt : it contains a data frame called cleanedData with 10299*68 dimension.
  - data_with_means.txt : it contains a data frame called result with 180*68 dimension.
* Finally, use data <- read.table("data_with_means.txt") command in RStudio to read the file. Since we are required to get the average of each variable for each activity and each subject, and there are 6 activities in total and 30 subjects in total, we have 180 rows with all combinations for each of the 66 features. 
