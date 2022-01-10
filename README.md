# Stock-Analysis

## Overview of Project
   This project was first to see how Steve's parents stock, Daqo, was performing. We wanted to find the daily and yearly returns for it after we wrote the code it became noticable that we need to find different stocks for them. We added code so we could analyze muliple stocks for them. When Steve saw how well that worked, he wanted us to see if we could do the whole stock market. This is where we used refactor to make the code more efficent to do a better anaylsis.
 
 ## Results
   The reason we wanted to start looking in to more stocks was Daqo did not have a postive return. When we started looking at more stocks, it became clear stocks did better in 2017 then 2018. Out of the 12 stocks that were analyzed, only two had positive returns in 2018. 
 ![This is 2017](2017stocks.png) ![This is 2018](stock2018.png)
 
 ### Execution Time
 When we ran the code for the 12 stocks in 2017 and 2018 the first time, the speed was pretty close to each other. They stayed that way after multi times running the code. ![Code Times](resources/VBA_Challenge_2017.png) We realized the more times we ran it the faster it got but only by hundereds of seconds. When we did the same thing for the whole stock market, the time only slowed down by hunderedsth with a lot more inputs. ![code times](resources/VBA_Challenge_2018.png)

## Summary

### Advantages and Disadvantages
   When looking at refactoring code there is a lot of simialarities between that and the original VBA script. The main advantage of refactoring is the time it takes to go thourgh a lot of data. You can write code to make it quick to see trends and dips when you are using a bigger sample. The main disadvantage we found is the code for the origanal is a lot easier and smoother to get to work. When you are working with more data you are more likely to have to write and rewrite code. We kept running into overflow error, but what it comes down to is what are you trying to do!
   ![overflow](overflow.png)
   
### Advantages and Disadvantages and How they apply
   If you have already narrowed your choice down, the disadvantages to refactoring play a big part. It is better to use the original. If you are just starting or trying to find a trend or flows in a big data set, it is alot better to work thourgh the bugs and errors to get more info. Then, you have all the info to make the best decision. In the end it is all what you are trying to get out of the analysis.
