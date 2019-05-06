#Mamas Cuban Kitchen

#Data Analysis Memorandum

  To perform analysis adjustments were performed. These data include anonymized transactional data from August through December 2018.
From the social media accounts, location data was added in as well if it were an event or a day on the street. Historical weather data was
added in from the weather underground website, specifically the temperature and precipitation. The data was grouped by date to create one 
observation for each date where sales occurred. The item column was converted to create a new item column that grouped the items into the 
staples that the truck sells. For example, instead of “3+ empanadas” and “3 empanadas with a side”, it now says “empanadas”. This allowed 
for less categories in the items column and an easier to understand data set. In the data grouped by date, the item column had each 
category counted and put in as a new column. Finally, the date column was used to create day of the week and month columns. The time column 
was turned into a lunch or dinner feature. 

   To begin analysis the structure and summary R function were run. This showed that there are categorial features and each with many
levels. To understand how these features, relate to Net Sales (as this is the main feature of interest) box plots and scatter plots of the 
data were run with each of the other features.  To further understand the relationship, ANOVA, t-tests or correlations were run on each 
feature with Sales. Finally, regression was used to see how much of the variability in sales can be determined by the other features.  
For the regression analysis, the dataset was subset to only include variables that would be known prior to the time of sale. For example,
features such as quantity sold are excluded for this analysis. These plots and tests show that overall these features do not describe much 
of the variability within Sales. This seems to be due to a lack of data. There is seasonality associated with the food truck business, but 
there is less than a year of data. This means that a full analysis on how that seasonality plays out can not be performed. Also, there are 
not that many observations in the final data set. 

   Despite the data limitations there are insights that can be found in the data. The top conclusions are that on days where the 
temperature is in near 70 sales are highest, providing a discount leads to more Sales and that events do better than parking in the street. 
The business decisions that can be made from these conclusions are that marketing/promotion should be highly implemented during months 
where the temperature is in the 70s. Also, more effort should be put into attending events, instead of parking in the street. The private
events and even public events such as Food Truck Fridays do well on Sales. Also, sending out discount codes to prior customers is a good 
way to entice them for return business. 
