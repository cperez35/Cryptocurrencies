## Overview

The goal of this project is to provide a report for an investment bank that is considering launching a new bitcoin investment portfolio. The paper details which cryptocurrencies are available for purchase and how they may be classified to develop a categorization system for this new investment. I'm using Crypto Compare's data to run unsupervised machine learning algorithms in order to finish this project.

## Results

I began by cleaning up the data to include only active trading cryptocurrencies with a specified algorithm and a comprehensive set of data. As a result, I now have 532 distinct cryptocurrencies. I then constructed a three-dimensional graph to demonstrate how the various cryptocurrencies are organised. Each point has a name as well as the algorithm that was used to produce it.
<img width="639" alt="Review_1" src="https://user-images.githubusercontent.com/83256206/137974828-15d65572-2970-43df-ae56-e4059ddd1884.png">


Then I made a two-dimensional graph to demonstrate the link between total coin supply and total coins mined, so you could see how one currency stacks up against the others. The name of the currency is included in each point.

<img width="550" alt="Review_2" src="https://user-images.githubusercontent.com/83256206/137974855-5e5f9473-b285-4b2f-b9f3-f59fd75752e7.png">


## Summary

There are four distinct groups seen in the three-dimensional graph. Most currencies fall into one of two categories, which are clumped together quite closely. The first group has a few distinct currencies that are separated from the others, whereas the second group just has one currency. This demonstrates that many currencies behave similarly, but a few stand out as outliers. These outliers might be overachievers or underachievers, but I'd have to do additional research to find that out. Looking at the total coin supply versus total coins mined graph is one way I can make a connection.
The majority of the data points for the two main categories are spread between 0% and 40% of the biggest currency by volume. The group with a few currencies is extremely near to 0% of the largest currency, but the group with only one currency is at 100% since it is the largest. I'd want to do further research on these cryptocurrencies by looking at their history price in order to better understand their performance. This would allow investors to determine how hazardous or reliable their investment is dependent on the many cryptocurrencies they invest in.
