# J124 Final Project Data Analysis and Visualization of WIC Participation Rates (Concentration on Pregnant and Postpartum Women)
## By Fernanda Frausto-Bonilla
* This dataset was downloaded as (12) .csv files from [U.S. Public Assistance](https://www.kaggle.com/datasets/jpmiller/publicassistance?select=WICAgencies2013ytd/).
* Link to [Google Sheet](https://docs.google.com/spreadsheets/d/1k-hFV07D_SuZsrD7_QWKM_obHQNqOTFNqP9yojNhaQQ/edit?usp=sharing)  with all .csv files cleaned.
# Data Analysis
## Notes:
* Download the "Pregnant_Women_Participation", "Postpartum_Women_Participation", and "Total_Number_of_Participants" .csv files for the years (2013-2016). 
* There is a total of (12) .csv files that should be cleaned in OpenRefine. When cleaning, I only needed to sort the State agency/Tribal organization columb, remove a duplicate column with no data (which was an extra Texas), format columns with dates to a (00/00/00) style, and format the data to 'number' rather than 'plain text.'
* Upload the cleaned .csv files to Google Drive. 
* In Google Sheets, import each .csv file into three separate sheets (as tabs) ("Pregnant_Women_Participation", "Postpartum_Women_Participation", and "Total_Number_of_Participants") and group together the data based on year. There should be a color-coded system for each year in each sheet (e.g. green for 2013, purple for 2014, yellow for 2015, and blue for 2016). All years' data on annual participation are color-coded in pink.
* My data is limited to the years (2013-2016) because those were the only years the data is available. The time frame for each year begins on October 1st and ends on September 1st of the following year. 
- In other words, 'Average Participation 10/12-09/13' refers to the year 2013, 'Average Participation 10/13-09/14' refers to the year 2014, 'Average Participation 10/14-09/15' refers to the year 2015, and  'Average Participation 10/15-09/16' refers to the year 2016.
## Analysis 1 ... Question: Which year saw the highest overall average (across all State agencies/Indian tribal organizations) WIC participation among pregnant women? Which one was the least?
### Step-By-Step Answer: 
1. Create a pivot table utilizing the 'Pregnant_Woman_Participation' sheet.  
- Add 'State Agency or Indian Tribal Organization' to the row. 
- Order the row by 'Ascending.' 
- Sort the row by 'State Agency or Indian Tribal Organization.' 
- Show totals for the row. 
- Add 'Average Participation 10/12-09/13', 'Average Participation 10/13-09/14', 'Average Participation 10/14-09/15', 'Average Participation 10/15-09/16' to values. 
- Categorize each value by SUM. 
- Compare the grand totals for each column and identify which average participation total is the highest. 
(<img width="856" alt="analysis #1 pt 1" src="https://user-images.githubusercontent.com/109619760/183837637-dd75ee26-10bf-4de6-b46b-c2b60a902693.png">
<img width="1287" alt="Screen Shot 2022-08-10 at 12 11 08 AM" src="https://user-images.githubusercontent.com/109619760/183837957-3e8f1f65-3654-4327-9468-11ce53e7995f.png">

### ANSWER KEY: 
* The year with the highest overall average WIC participation among pregnant women is the 2013 (10/01/12 - 09/01/13). 
* The year with the lowest overall average WIC participation among postpartum women is 2016 (10/01/15 - 09/01/16)


* Which population group (e.g. postpartum women, pregnant women, etc.) participated more actively in WIC services between 2013 and 2016? Was any group exceptionally active? 
## Analysis 2 ... Question: Among pregnant women, which three state agencies or Indian tribal groups participated the most?
## Analysis 3 ... Question:Among postpartum women, which three state agencies or Indian tribal groups participated the most?
## Analysis 4 ... Question: What is the percent change across the years (2013-2016) in WIC participation across all groups and all state agencies or Indian Tribal Organizations?
## Analysis 5 ... Question: What percentage of total WIC participants are postpartum women and pregnant women?

# Story Pitch and Summary

On a U.S. national basis, the cost of living and raising children has progressively increased rapidly. According to data from Statista Research Department [(https://www.statista.com/statistics/216426/average-costs-of-raising-a-child-from-birth-to-age-18-in-the-us--in-2010-by-category/)] , the average cost of feeding a child in the U.S. from birth to age 18 was $39,060 in 2013. This expense equals an average annual cost of $2,170 for feeding a child when divided by 18 (the total number of years it predicted spending money on feeding a child). As a result, more and more mothers (including soon-to-be-mothers) struggle to give their kids a healthy, quality diet and are compelled to deal with food insecurity head-on. To assist mothers and children facing food insecurity, the Federal and State government provide special funds through the Special Supplemental Nutrition Program for Women, Infants, and Children (commonly known as "WIC") to assist low-income women and children up to age five who are at nutritional risk. These funds are used to provide supplementary food, infant formula, medical care, and nutritional counseling. In my story pitch, I am seeking to break down WIC participation rates by categories and understand which population groups utilize services the most. These categories include the following: postpartum women, pregnant women, and ---------. 

The purpose of this story is to shed light on WIC participation and to answer questions such as "Which population groups (e.g. pregnant women, postpartum women, etc.)make up the largest percentage of WIC participants?" or "Which state agency or Indian tribal organization has the highest relative par ticipation rate?" I think that by looking at the statistics, we can build a framework for deciding which population groups should receive more services and for figuring out where and why they do.
### Note: A limitation to my story analysis is that it's data relies on the period (2013-2016) because it was the only available data for these population groups specifically. 

this data is to break down the participation rates of different categories in regards to WIC. By this I mean, I will analyze which groups which include postpartum women, pregnant women, etc. are utilizing WIC and determine data analysis related concerns such as which group utilizes the program most, etc. My data study, in my opinion, is relevant since it shows comparisons between groups for the period (2013–2016) and raises issues regarding which populations normally need greater support and what the federal government should target with more resources.


