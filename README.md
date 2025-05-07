# M0 Business Data Analysis Final Project
<p align="center">
 Streaming platforms rose to the top with their business model, attracting millions of concurrent subscribers. Netflix has been a dominating force in this sector of entertainment. However, many competing streaming platforms emerged, attempted to carve a space in this profitable sector. Disney+ is one of these competing forces, yet it has struggled considerably. 
</p>

![](data/202592_408322_DIS_LOGO_600x324_with-shadow.png)

## Business Understanding

### Business Problem
#### Why is Disney+ struggling to compete with other top streaming services?
 
### Industry
Marketing/Entertainment

### Company
<ins>Disney+</ins>, Netflix, Hulu, Prime Video

## Project Objectives

### Data Lifecycle
As a data analyst, I used each phase of the data life cycle to complete my work. This allowed me to stay focused on my task. For this task:
![](data/datalifecycle.png)
- I am presented with the business problem.
   - Aside from data collection, I also viewed news resources and overviews of the companies I would focus on.
     
- I collect the data (Dataset found on [Kaggle](https://www.kaggle.com/datasets/ruchi798/tv-shows-on-netflix-prime-video-hulu-and-disney)).
   - In this scenario, the data collected included categories like movie/show titles, ratings, and if the platforms held the media.
     
- I process the data.
   - With this dataset, I sorted/filtered specific columns and removed blank spaces. I also use functions to pull key metrics.
     
- I analyze the data.
   - With a clean dataset and metrics, I pull insights and combine them with my knowledge on the subject.
     
- I create visuals to present the data.
   - To better articulate my findings, I create visuals that drive my conclusions home.

***

### Data Types
Explain the data types in the dataset (e.g., numeric/non-numeric, quantitative/qualitative, discrete/continuous).
***
### Excel Analysis
<p align="center">
To begin working on the data in Excel, I had to adjust Excel parameters to detect the commas in the .csv file as cells. Once the .csv was transferred onto Excel, I was able to sort and filter the raw data to make it easier to work with. I filtered the blank entries and sorted the data in descending order based on the Rotten Tomatoes Scores column. Once this was done, I then used functions to calculate summary statistics. The data collected information on if a platform had a show by using 0 or 1. The data displayed 1 if it contained the show, and 0 if it did not. Therefore, I was able to use a COUNTIF function to count how many 1s appeared in the column for each streaming platform. This gave me a total count of shows that each platform had.
</p>
<p align="center">
Next, I wanted to find the top-rated show for each platform. To do this, I had to use a MATCH function within an INDEX function to find where the 1 appeared first in the sorted column, then display the title of the show that correlated with the matching cell. Doing this for all platforms while maintaining an absolute cell reference for the range of the show titles column.
</p>

*** 

### Python Analysis
Summarize the tasks performed in Python.

## Conclusion:
Add three points about what you learned in this module.

> [!NOTE]
>  This is a fictitious scenario created by the github author for academic purposes only.
