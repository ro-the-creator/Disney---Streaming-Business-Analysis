# M0 Business Data Analysis Final Project

## Business Understanding
 
### Industry
Marketing/Entertainment

### Company
Disney+, Netflix, Hulu, Prime Video

## Project Objectives

### Data Lifecycle:
Include an image of the data lifecycle and explain how each stage could potentially apply to your business scenario.
### Excel Analysis:
To begin working on the data in Excel, I had to adjust Excel parameters to detect the commas in the .csv file as cells. Once the .csv was transferred onto Excel, I was able to sort and filter the raw data to make it easier to work with. I filtered the blank entries and sorted the data in descending order based on the Rotten Tomatoes Scores column. Once this was done, I then used functions to calculate summary statistics. The data collected information on if a platform had a show by using 0 or 1. The data displayed 1 if it contained the show, and 0 if it did not. Therefore, I was able to use a COUNTIF function to count how many 1s appeared in the column for each streaming platform. This gave me a total count of shows that each platform had.
Next, I wanted to find the top-rated show for each platform. To do this, I had to use a MATCH function within an INDEX function to find where the 1 appeared first in the sorted column, then display the title of the show that correlated with the matching cell. Doing this for all platforms while maintaining an absolute cell reference for the range of the show titles column.
### Python Analysis
Summarize the tasks performed in Python.
### Data Types:
Explain the data types in the dataset (e.g., numeric/non-numeric, quantitative/qualitative, discrete/continuous).
### Conclusion:
Add three points about what you learned in this module.

(This is a fictitious scenario created by the github author for academic purposes only)
