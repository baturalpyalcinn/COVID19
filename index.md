# COVID19 Data Visualization with Python

- This is my [data source.](https://ourworldindata.org/coronavirus-source-data)  
- You can follow me on [Twitter](https://twitter.com/BaturalpYalcin) and check my [GitHub Page](https://github.com/baturalpyalcinn) to be kept updated about my work.

### March 25 (Latest)
**For Comparitive Plots:** You can find comparitive plots of the countries in the world from [here.](March_25/Covid19_March_25_Plots.html)  
**For Forecast Study:** 
- You can find Linear Regression forecast for some specific countries [here.](March_25/Covid19_March_25_Forecast_LR.html)  
- You can find Damped Exponential Smoothing forecast for some specific countries [here.](March_25/Covid19_March_25_Forecast_ES.html)  
**For Turkey:** You can find plots and figures related to Turkey from [here.](March_25/Covid19_March_25_Turkey.html)   

**Some *updates*:**  
- I have added new countries that I made forecast for.
- I make hyperparameter tuning for exponential smoothing method before make a forecast.

**My forecasts for each country are based on whichever method works best for a specific country.**


| Country      | March 24 (Actual) | March 25 (Forecast)    | 
| :---        |    :----:   |          ---: |
| World exc. China      | 335,069      | 378,307   |
| Turkey      | 1,872      |  2,176  | 
| Italy   | 69,176       |  73,882    | 
| United States      | 55,231       | 67,324  | 
| Spain   | 39,673       |   45,102  |  
| United Kingdom   | 8,077       | 9,369    |   
| France   | 22,302       |  25,253   |  

### March 24
**For Comparitive Plots:** You can find comparitive plots of the countries in the world from [here.](March_24/Covid19_March_24_Plots.html)  
**For Forecast Study:** You can find forecast for some specific countries [here.](March_24/Covid19_March_24_Forecast.html)  
**For Turkey:** You can find plots and figures related to Turkey from [here.](March_24/Covid19_March_24_Turkey.html)   

**Some *updates*:**  
- I have added damped exponential smoothing method under the forecast section to estimate future total cases.
- I started to keep track of daily testing number for Turkey. You can see the plots under the Turkey section.  

My daily forecasts for some countries by using damped exponential smoothing method (ES) and linear regression method (LR). See the plots below!  

| Country      | March 23 (Actual) | March 24 (Forecast) (ES)    | March 24 (Forecast) (LR) |
| :---        |    :----:   |          ---: |           ---: |
| Turkey      | 1,529      | 1,859 (-4%)   | 1,847 (-7%)  |
| Italy   | 63,927       | 68,955 (-4%)     | 72,866 (+70%)  |
| United States      | 46,442       | 60,540 (+60%)  | 55,046 (+%2) |
| Spain   | 33,089       | 38,603  (-16%)    |  38,550 (-17%) | 
| United Kingdom   | 6,724       | 7,801 (-20%)     |  7,944 (-10%) |

- **Purple** curve performs the best according to recent updates in **Turkey**.    
![Turkey Plot](March_24/turkey_purple.PNG)  

- **Red** curve performs the best according to recent updates in **Italy**.  
![Italy Plot](March_24/italy_red.PNG)  

- **Yellow** curve performs the best according to recent updates in **the US**.  
![USA Plot](March_24/us_yellow.PNG)  

- **Green** curve performs the best according to recent updates in **Spain**.  
![Spain Plot](March_24/spain_green.PNG)    

- **Green** curve performs the best according to recent updates in **the UK**.  
![UK Plot](March_24/uk_green.PNG)  

### March 23
**For Comparitive Plots:** You can find comparitive plots of the countries in the world from [here.](March_23/Covid19_March_23_Plots.html)  
**For Forecast Study:** You can find forecast for some specific countries [here.](March_23/Covid19_March_23_Forecast.html)  
**For Turkey:** You can find plots and figures related to Turkey from [here.](March_23/Covid19_March_23_Turkey.html)    

**Here is my forecasts of total cases for the countries that could not flatten the curve! Check out the plots below.**

| Country      | March 22 (Actual) | March 23 (Forecast)    | March 23 (Error) |
| :---        |    :----:   |          ---: |           ---: |
| Turkey      | 1,236       | 1,605   | 1,529 (26%) |
| Italy   | 59,138        | 66,567      |  63,927 (55%) |
| United States      | 35,206       | 42,199   | 46,442 (-38%)
| Spain   | 28,572        | 33,502      |  33,089(9%)
|United Kingdom   | 5,683        | 6,917      |  6,724 (19%) |

![Turkey Plot](March_23/turkey_forecast.PNG)
![Italy Plot](March_23/italy_forecast.PNG)
![USA Plot](March_23/us_forecast.PNG)
![Spain Plot](March_23/spain_forecast.PNG)

### March 22
[Here](Covid19_March_22.html) is the March 22 version of my work.  
**For Turkey:** You can find plots and figures related to Turkey from [here](Covid19_March_22_Turkey.html).  

*"Here is a new plot for Turkey depicting the capacity of the hospitals in Turkey and how long they can accomodate new patients under exponential growth. According to the plot, if the number of COVID 19 cases continue to grow exponentially, there will not be enough hospital beds until March 30th assuming that every patient will be hospitalized."*  

![New Plot](new_plot.PNG)

### March 21
[Here](Covid19_March_21.html) is the March 21 version of my work.


### March 20
[Here](Covid19_March_20.html) is the first version of my work.


