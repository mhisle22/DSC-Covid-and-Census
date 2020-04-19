# DSC-Covid-and-Census
Data science project using US Census data to model and analyze the spread of COVID19.  
Developed using Google Colaboratory, and is best viewed using said platform or a Jupyter Notebook.


## Please note that this project is in development and many aspects of it can/will change.

# Outline

This is an exploratory project aimed at using US Census data from 2017 to make observations on the spread of the novel virus COVID19 in the year 2020. Data is collected and processed from two different sources, both of which were taken from Kaggle: US Census Demographic Data, containing standard census data on US counties, and US counties COVID 19 dataset, a dataset taken from the New York Time's report on the number of cases and deaths caused by the virus in US counties since the first reports of cases in Washington state. All counties in the United States are accounted for, including data for Washington D.C. Links to the two datasets can be found below.

This project seeks to answer a few common questions on the spread of this virus using basic geographical data: 
* Are more populous counties more significantly affected?
* Is there a trend between the overall poverty/wealth of a country and its number of cases? This can be viewed with a number of variables taken from the census, such as poverty rate, income per capita, etc.
* Are certain states proportinoally more affected than others (i.e.- has the number of cases largely followed population, or are the preventative measures of certain state governments cause noticeable improvements? Are other factors involved (coastal, climate, border state, etc.))
* Is there a difference between men and women?
* Are counties with a higher proportion of commuters/work from home/walkers/transit users more affected?
* Does unemployement have a large affect on number of cases?
* Does the US classification of ethnicity (non-Hispanic white, Hispanic, Black, Asian, Native, Pacific Islander) cause noticeable differences?
* What trends can be observed over certain time periods

By aggregating, visualizing, and building several different statistical models with this data, we hope to give a general insight on whether Census data can be used to make predictions on the spread of this virus. 

At the time of the creation of this project (Spring 2020), data for the spread of the virus is still developing, as the COVID19 virus was still widespread within the country at the time. Because of this, the NYT US County COVID19 dataset continually gained new information. It is highly possible in the future that the virus will no longer be active in the US, and this data will no longer be in flux. In addition to this, assuming the virus will start to dissappear, completely new trends will appear later on, which will need separate analyses focusing on this new data.    
 
  
https://www.kaggle.com/muonneutrino/us-census-demographic-data   
https://www.kaggle.com/fireballbyedimyrnmom/us-counties-covid-19-dataset
