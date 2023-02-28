# Overview
The goal of this project is to provide an investment bank with a report on creating a new bitcoin investment portfolio. The report includes the description of cryptocurrencies that can be purchased, and how they can be classified to create a classification scheme for the new investment. To complete this research, unsupervised machine learning algorithms are run on data from Crypto Compare.

## Results
Data cleaning was done to include only cryptocurrencies that were being traded using a specific methodology and a full set of data, resulting in 532 different cryptocurrencies. A three-dimensional graph was created to display how the various cryptocurrencies are organized. Each point is identified by name and the algorithm that created it.

markdown
Copy code
![Three-dimensional graph](https://user-images.githubusercontent.com/83256206/137974828-15d65572-2970-43df-ae56-e4059ddd1884.png)
Additionally, a two-dimensional graph was made to demonstrate the link between total coin supply and total coins mined, so that the comparison can be made between one currency and others. The name of the currency is included in each point.

markdown
Copy code
![Two-dimensional graph](https://user-images.githubusercontent.com/83256206/137974855-5e5f9473-b285-4b2f-b9f3-f59fd75752e7.png)
## Summary
The three-dimensional graph shows four separate groups. The majority of currencies can be divided into two closely related groups. The first group has several unique currencies that are isolated from the others, while the second group only has one currency. This indicates that most currencies perform consistently, with a few exceptions. Further research would be needed to determine if these outliers are overachievers or underachievers. One way to make a connection is to analyze the graph of total currency supply vs total coins mined.

Between 0% and 40% of the largest currency by volume, the majority of the data points for the two major groups are dispersed. The group with several currencies is very close to having 0% of the largest currency, but the group with just one currency has 100% of the greatest currency. To better understand the performance of these cryptocurrencies, it would be useful to conduct additional research on their historical prices. This would enable investors to assess the risk or dependability of their investment based on the many cryptocurrencies they invest in.
