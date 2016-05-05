# d3_visualization:Comprehensive Analysis of Various Visa Issued to the Different Nationalities into India- Udacity Project-6
by Karthik Elangovan, in fulfillment of Udacity's [Data Analyst Nanodegree](https://www.udacity.com/course/nd002), Project 5

## Summary

This data visualization has a comperhensive study of Various Visa Issued to the Different Nationalitie by India embassy. 

I would be answering the following question:

  1.Do people travel to india just for tourism, or india is a popular destination for business and education.
  2.Did the cricket world cup in 2010 brought more people and boosted tourism in the nation.
  3.Why does India building world’s most expensive wall at its border.

## Exploratory Data Analysis and Cleaning (Python-pandas):

I downloaded the data from [india.gov.in](https://data.gov.in/catalog/issuance-visa-various-foreign-nationals-against-various-categories-visas). The data contain count of how many visa are approved every day on different categories for differnt nationalities. The was grouped by to answer the above questions using python-pandas. 

Intial find showed that there was increasing trend in visa approved every year. This was clearly seen in line plot. To have better view on how many visa was approved on each different categories i tried ploting stacked bar. As tourist visa peaked then all other visa type i find a grouped bar as a better choose. finialy i used a line plot to show how many visa has been approved for top 5 county as they combained together contribute 60% of total visa approved. 

## Data Visualization using (D3.js and dimple.js):

I decided to improve  the visualization and add some intration using D3.js and Dimple.Js.

  1.I improved the line graph by  adding tool tip so show the total count of the visa approved. 
  2.I added line grid to improve the visulisation.
  3.I thought both stacked bar and grouped bar could help in understanding the count on differnet visa category approved. As stacked bar was very usefully as comparision of one category with other and group bar can give a good insight on how much each type of visa counts. I did included both graph and add some intraction during transtion from one to another.
  4.I added text to support my finding and answer the questions with the help graphs.
  
### Feedback
I intervied 3 individual and askinng for their feedback on the data visualization with a small set of question

### Interview #1
>What do you notice in the visualization?
  It is easy to interpret, I see a considerable increase in the issue of visa in 2012 and a drop after that, the explanation is over whelming on it. To me, line graph on annual visa approval for different categories & bar graph on top 5 countries would be more appealing. 
>What questions do you have about the data?
  What could be the particular reason for the drastic increase in the issue of tourist visa during 2011-12? Does any particular optimistic projection happened? 
>What relationships do you notice?
  There was an increase in relationship till 2012 and later gradual drop towards 2013.
  
### Interview #2
What do you notice in the visualization?
Overall I noticed that there is positive trend of number of people coming to india for tourism.

  
