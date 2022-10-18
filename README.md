# Stocks Analysis

## Overview of Project
###### Explain the purpose of this analysis

This project is to refactor or an existing codebase so that it is more efficient and is more robust to analyze stocks of any year in a specific data set.
 We have updated the code base to loop over the relavent stock ticker just once to collect stock volume info. It's performance over a year is collected and presented. 

## Results
###### Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.

As we can observe, overall the performance of stocks in 2018 was far worse than in 2017. We can see this in the images provided below.
![This is an image](https://imgur.com/jUumeOl.png)
![This is an image](https://imgur.com/JvhHZAh.png)
Furthermore there is no correlation with volume to expected return. 
Two stocks consistently performed well over the two years, which were ENPH and RUN. Due to our refactored code we can also see that the execution time improved by an order of 10 or more.

## Summary 
###### What are the advantages or disadvantages of refactoring code?
###### How do these pros and cons apply to refactoring the original VBA script?

In general refactored code can be updated to be better, both in efficiency and ability. However this can become time consuming, spending time to redecipher other people's code or code you wrote a long time ago.
You could  end up making the code even more complicated, instead of everything being concise standalone functions they start becoming an amalgamous monolithic function that is difficult to comprehend. 
Algorithm efficiency and scope of the project must be carefully balanced when tackling any project. 

The orifinal VBA script perfectly did what we asked in our original mission statement. It is not too large for our two sheets of data sets. However it wouldn't be robust enough for any small changes in the data set 
such as year or format of the financial data. It was also a slower script in looping over various tickers that are not relavent to the ticker we are collecting information on. 
