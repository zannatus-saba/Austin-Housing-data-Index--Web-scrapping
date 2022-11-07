# Austin-Housing price-data-Index--Web-scrapping

I have worked with real estate data of the Austin metropolitan area of the state of Texas, USA. 
I have focused on data from 2015 for getting housing activities in Austin from the website of the Texas Real Estate Research Center, which is a research center operated at Texas A&M University. This research center has data for each county in the USA. I have specifically filtered out data for “Housing Activity for Austin County”. From here, I scrapped the quarterly housing price data data. I used All-Transactions House Price Index for Austin-Round Rock-Georgetown, TX (MSA). I scrapped the CSV file and got the quarterly index from Quarter 1 2015 to Quarter 3 2022.  

The data Texas Real Estate Research Center website was from January 2011. But surprisingly, for some variables, there were no data before January 2015. I had to sort the data for that purpose. After scrapping the whole data table, I omitted the rows from January 2011 to December 2014 using python coding. Otherwise, it would be tedious  to do the analyses. For the Price Index dataset, I reduced my dataset and used data from 1st quarter of 2015 until the 1st quarter of 2022.  
