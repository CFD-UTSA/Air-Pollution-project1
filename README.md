# Air-Pollution

Project 1 : Air Quality
Points:   100 points
 Due March 16th 2021


The objective of this project is to use Pandas framework to: 
a. access data from an open source repository b. conduct statistical analysis. C. visualize the output, d. analyze and interpret the results.

Data source: https://openaq.org/#/locations?page=1
Python Template: 

The data source has access to pollution data, including, PM2.5, PM10, ozone (O3), sulfur dioxide (SO2), nitrogen dioxide (NO2), carbon monoxide (CO), 
and black carbon (BC) measurements in 130 different countries. 
Navigate to a specific dataset's page to view measurements and find technical information on collection methods. 
Datasets are part of a pilot to incorporate low cost sensor data into the platform.   (Note: PM: particulate matter)



1.  Pick 3 locations and 4 different pollutants (e.g. CO, Pm2.5, No2) data for around 5 years. 
 Background research: Explain the significance of these pollutants in the atmosphere. [ 5 points]

2.  Write panda code to extract information about the datasets. Use Pandas data frames.  [ 5 points]

3.  Write pandas code to conduct time-series statistical analysis for each of the pollutants. [20 points]
(this includes:    Across the 5 years:  
Yearly mean vs. pollutant, 
 compare the Monthly averaged mean for all the pollutants,    
  Mean for each day of the weak for all the pollutants i.e. mean over all the 5 years on Monday, Tuesday ...
  daily-averaged mean i.e. mean over all the 5 years for all the months on 1,2,3,....30 days.
  hourly-averaged mean i.e. calculate the mean over all the 5 years for all the months for all the days at 1pm, 2pm, 3pm..... 12pm  )..

4.  Conduct correlation analysis.  [20 points]
(What is the correlation between different months of the year from the yearly averaged mean for each of the pollutants
 
What is the correlation between different pollutants?  

5.  Conduct FFT analysis and plot the dominant modes.  Reconstruct the physical data from domain fft modes (look at the data and e.g. pick 10 modes or 20 modes to reconstruct to the data).  [10 points]

6. Fit a nonlinear correlation regression between 2 pollutants.  Plot the fitted data and the original data.  [10 points]

7. Plotting:   Use different plotting schemes (histograms, bar, stem etc) to explain the data. (e.g. time-series plots, correlation plots, regression analysis, etc) [10 points]

8. Conclusions and discussion:  Use the above plots and analysis to explain the the trends and patterns of the pollutants in the location that you have selected.  [ 20 points]

