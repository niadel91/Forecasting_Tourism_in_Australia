# Forecasting_Tourism_in_Australia
Analysis of different Forecasting techniques on a time series dataset to forecast the number of tourists in Australia
<br>
<br>
<br>


### Data Source
visitors dataset from fpp2 package. These data include monthly Australian shortterm overseas visitors data, May 1985–April 2005.
<br><br>

### Approach
<ol>
<li> Made a Time Plot of the data, describing the main features of the series.
</li>
<li>Split the data into a training set and a test set comprising the last two years of available data.
</li>
<li>Forecast the test set using Holt-Winters’ multiplicative method and used the output to analyse whether Multiplicative Seasonality is necessary here.
</li>
<li>Forecast the two-year test set using each of the following methods:
    <ul>
    <li>ETS Model
    </li>
    <li>Additive ETS model applied to a Box-Cox transformed series 
    </li>
    <li>Seasonal naïve method 
    </li>
    </ul>
</li>
<li>Which method gives the best forecasts?  Does this method pass the residuals test?
</li>
</ol>
<br><br>

### Conclusion
Surprisingly, the Seasonal naïve method was able to provide the best forecasts but it could not pass the residuals test.
