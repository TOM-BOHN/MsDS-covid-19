## MsDS-covid-19

## Abstract
Analysis of COVID-19 data for global and US datassets. Exploratory data anlaysis in R to identify how the data interacts and connects.

## Conclusion

After completing the analysis of data, visualization, and modeling, we can conclude the following:

| Question                                  |  Conclusion                                  |
|-------------------------------------------|----------------------------------------------|
| What Does the Trend of Cases and Deaths look like overall for the US?         | This plot displays the cumulative total for the US. Given the extremely large number of cases and the log scale, it is hard to tell for recent data how much the chart is increasing and if cases and deaths are going up on a daily basis. Overall, it displays that there was a sharp increase initially, but then cases began to taper off and grow slower than exponential. Looking at the zoomed in chart on 2022 (with the log scale removed, we see growth that looks more linear than exponential. | 
| What Does the Trend of Cases and Deaths look like overall for Illinois? | Comparing Illinois to the US totals, we see a similar pattern. Extreme growth of cases initially, then it tapers off on the log scale graph. Overall, the macro patterns look the same for both. |
| What is the Largest Total Deaths and Date in the covid19 in the US Plot?      | The largest data point for the US is 1,122,724 total cases and occurs on 2023-03-09. |
| How do New Deaths and New Cases Trend Over Time in the US?  | When we observe new cases and deaths, we see a peak for growth occurring around the beginning of the year in 2022. We then actually see the number begin to trend down. Zooming in on the data after 2022 and removing the log scale, we see some fluctuations in the data, but new cases and new deaths appear to be mostly flat, indicating linear growth. |
| How do New Deaths and New Cases Trend Over Time for the State of Illinois?       | When we observe new cases and deaths, we see a peak for growth occurring around the beginning of the year in 2022. We then actually see the number begin to trend down. Zooming in on the data after 2022 and removing the log scale, we see some fluctuations in the data, but new cases and new deaths appear to be mostly flat, indicating linear growth. |
| Create a List of the Top 10 Best and Worst State for covid19 Deaths per Thousand People?          | Looking at the states with the lowest deaths per thousand, we see that remote locations such as islands or low population locations seem to do better with deaths. There is less of an obvious pattern here for the top 10 states with the highest deaths per thousand people. If we had to categorize them based on properties, we might say they skew towards the southern US region and are more republican than democratic in their political views. |
| Can we create a usable predictive model for covid19 deaths per thousand people using our US dataset?     | In short, No. A significant predictive model cannot be created with the 3 state level variables in our dataset.  Additional variables will need to be explored to develop a usable model. |
