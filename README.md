# Final Project QSS20 22W
## Student Impact Practicum investigating the effects of race, gender, and the Covid-19 pandemic on the disabled community within START Services

# AUTHORS: Josephine Kim, V Quidore, Raniyan Zaman, Kai Zhou

#### Check out our comprehensive [final report](https://github.com/vquidore/final-project-qss20/blob/main/Final_Project___SIP_.pdf) concerning the backgroun, methodology, and results of this project and a discussion of future steps to be taken!

## Usages

- The first .ipynb file that should be run is 00_Data_Loading_Cleaning, then 01_look_by_the_numbers, then finally 02_Topwords_TopicModeling

### Code 

|**Script/Notebook**|**Takes In**|**Does**|**Outputs**|
|:------------------|:-----------|:-------|:----------|
|[00_Data_Loading_Cleaning](https://github.com/vquidore/final-project-qss20/blob/main/code/00_Data_Loading_Cleaning.ipynb)|All four excel datasets found in the files directory|Reads .xlsx files into Pandas dataframes, subsets data by race and gender into four new dfs|will output csvs of cleaned, subsetted, dfs to the output directory|
|[01_look_by_the_numbers](https://github.com/vquidore/final-project-qss20/blob/main/code/01_look_by_the_numbers.ipynb)|Takes in four cleaned csvs from output directory|Provides visualizations of responses to Yes/No and Likert scale questions by race and gender of patient|Creates visualizations within notebook w/ screenshots uploaded to the output directory|
|[02_Topwords_TopicModeling](https://github.com/vquidore/final-project-qss20/blob/main/code/02_Topwords_TopicModeling.ipynb)|Takes in four excel files in files directory|Provides Topic Modeling analysis on caregiver responses to open-ended questions|Outputs interactive visuals in notebook (because interactive, not in output directory)|
### [Files](https://github.com/vquidore/final-project-qss20/tree/main/files)

- The files directory contains four datasets on disabled patients provided by START Services of New Hampshire. 


### [Outputs](https://github.com/vquidore/final-project-qss20/tree/main/output)

- Above is a link to our output directory!
