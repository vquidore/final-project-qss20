# Final Project QSS20 22W
## Student Impact Practicum investigating the effects of race, gender, and the Covid-19 pandemic on the disabled community within START Services

# AUTHORS: Josephine Kim, V Quidore, Raniyan Zaman, Kai Zhou

## Background

## Overview of project

### Plan 

- Subset THE DEMOGRAPHICS dataset by: Gender (Male/Female) Race

- Merge the demographics data and the Start FEIS data by patient ID # 

- Clean data so only relevant columns are left (Demographic data + family input)

- We plan firstly to look at the spectrum of responses comparing available services/client mental health (as the answers are on a scale) and turn this into numerical data in order to quantify the quality of each subset’s degree of care.

- We then plan to conduct topic modeling on the column in which families discuss where care is lacking in order to find the most popular/most desired methods of care that START did not provide.

- We also plan to conduct topic modeling and sentiment analysis on the column in which families offer advice to their caregiver in order to form a rough idea of the quality of care and how it may vary across demographic groups. 
- We also are interested to see if these responses’ sentiment scores will trend in a specific direction, indicating biases in those who actually responded to the survey.

## Usages

- The first .ipynb file that should be run is 00_Data_Loading_Cleaning, then 01_look_by_the_numbers, then finally 02_Topwords_TopicModeling

### Code 

|**Script/Notebook**|**Takes In**|**Does**|**Outputs**|
|:------------------|:-----------|:-------|:----------|
|[00_Data_Loading_Cleaning](https://github.com/vquidore/final-project-qss20/blob/main/code/00_Data_Loading_Cleaning.ipynb)|All four excel datasets found in the files directory|Reads .xlsx files into Pandas dataframes, subsets data by race and gender into four new dfs|will output csvs of cleaned, subsetted, dfs to the output directory|
|01_look_by_the_numbers|Takes in four cleaned csvs from output directory|Provides visualizations of responses to Yes/No and Likert scale questions by race and gender of patient|Creates visualizations within notebook w/ screenshots uploaded to the output directory|
|02_Topwords_TopicModeling|Takes in four excel files in files directory|Provides Topic Modeling analysis on caregiver responses to open-ended questions|Outputs interactive visuals in notebook (because interactive, not in output directory)|
### [Files](https://github.com/vquidore/final-project-qss20/tree/main/files)

- The files directory contains four datasets on disabled patients provided by START Services of New Hampshire. 


### Outputs

## Commentary and Future Uses/Directions/Discussion
