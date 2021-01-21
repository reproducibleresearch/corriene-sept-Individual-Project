# corriene-sept-Individual-Project

In this respository there are 3 folders: data, code, and results. 

The data folder contains the 3 data files used to make the graphs and tables: national-history.csv (contains information about hospitalizations), us.csv (contains information about deaths and cases nationwide), and us-states.csv (contains information about deaths and cases at the state level). us.csv and us-states.csv were obtained from the NY times github, https://github.com/nytimes/covid-19-data. Note that this information is updated daily; the datasets I used were downloaded on January 19, 2020 and the tables and graphs were made for January 17, 2020. national-history.csv was obtained on January 19, 2020 from https://covidtracking.com/data/download (summmary data for the United States.)

The code file is BST 270 Individual Project.Rmd and is contained in the code folder.

The results are contained in the results folder in the file BST_270_Individual_Project.pdf.

To reproduce these results, download all 3 datasets from the data folder and the code from the code folder. Replace the paths in the code file to where your 3 datasets are located. The following packages are used to run the analysis: ggplot2, stringr, zoo, lubridate, tidyverse, kableExtra, and readr. The version of R that was used is R 3.6.0. R Studio was used for the analyses. Running the code file should then produce results identical to those located in the results folder. 
