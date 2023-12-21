# Data Visualisation Challenge
## Summary
In this challenge, the data of 249 mice were recorded as they underwent cancer tumor treatment for ten different potential drugs which was then analysed and visualisation techniques implemented.
## Provided Data/Inputs
The data provided by Pymaceuticals Inc, included the following for each mouse:
* Gender
* Age (months) at beginning of treatment
* Initial weight (g)
* Tumor Volume (mm3) at intervals of 5 days (also referred to as Timepoints)
## Data Analysis/ Outputs
Using the data provided, it was merged and cleaned to remove any duplicate mouse/timepoint recordings.
The following visualisations were created using this data:
* Tumor volume statistical values were then calculated for each drug regimen:
  * Mean
  * Median
  * Variance
  * Standard deviation
  * Standar error mean
* Bar graph of the count of timepoints recorded for each drug regimen
* Pie chart showing spread of male vs female mice used in this research
* Box plot, including outliers identified, of final tumor volumes for four selected drug regimens
* Line graph showing tumor volume over time for a selected mouse undergoing Capomulin treatment
* Scatter plot and regression model of mouse weight versus average tumor volume for mice undergoing Capomulin treatment.
## Installation and Running
For this code to run successfully, python is required to be installed along with the pandas tool library and either Jupyter lab or Jupyter notebook. One method to install these programs is to download Anaconda - link below. To run this code, open the file within Jupyter, ensure that the input files are directed correctly and run! 
Anaconda install: https://docs.anaconda.com/free/anaconda/install/

## External Assistance
This code had assistance in two instances:
* AskBCS Learning Assistant for dropping duplicate rows. I had identified the duplicate mouse however needed assistance with the .isin function. 
* from my Instructor, Sean Whitehead, to write the 'for' loop to append the final tumor volumes of the four selected drug regimens.
