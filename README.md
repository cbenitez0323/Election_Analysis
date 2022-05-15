# Election_Analysis

## Overview of Election Audit: 
The purpose of this election analysis is to read the file containing information of each ballot and then calculating the votes to each canidate and based on that information, declaring a winner of the election.

## Election-Audit Results: 

- The total votes cast in this election are 369,711 votes.
- The votes came from three counties; Jefferson, Denver, and Arapahoe. Jefferson had 38,855 votes cast which is 10.5% of the total votes. Denver had 306,055 votes which is 82.8% of the total votes. Finally, Arapahoa had 24,801 votes which is 6.7% of the total votes. 
- Denver had the largest amount of votes with 306,055 votes. 
- The votes were for three canidates; Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane. Stockham had 85,213 votes which is 23.0% of the total votes. DeGette had 272,892 votes which is 73.8% of the total votes. Finally, Doane had 11,606 votes which is 3.1% of the total votes. 
- Diana DeGette won the election with 272,892 votes which is 73.8% of the total votes.

<img width="286" alt="Screen Shot 2022-05-15 at 4 50 06 PM" src="https://user-images.githubusercontent.com/102255823/168494344-7068d5af-aa03-4b18-9f05-1caaa95a0842.png">

## Election-Audit Summary: 

This code can be used to calculate the total number of votes, the votes from each county, and the votes for each canidate of othe elections. This is because the code starts by finding each county and canidate from the data file provided. 

One way it may need to be modified is if the data file being read by the code contains the saem information but in a different order. For example, the file used contained the ballots ID, the county and the canidate in that order. But if it were in any other order, the code will have problems because it will bring in data from the worng area of the file. Therefore the indexing would have to be modfied. 

<img width="294" alt="Screen Shot 2022-05-15 at 5 26 20 PM" src="https://user-images.githubusercontent.com/102255823/168494531-106e3352-b4c0-49a0-9994-02028b9c0a79.png">

Another modification is when the election is at a national level. The analysis would then need to include a way to catagorize the votes by state. Therefore there would be an addition to the code that included creating a list and dictionary for states and then following the same logic when calculating the number of votes and percentage as used to find the canidates and counties.
