# Election_Analysis

## Overview of Election Audit
A Colorado Board of Elections employee has tasked me with the following tasks to complete an election audit of a local congressional election in Colorado.

1. To calculate the total number of votes cast.
2. To get a complete list of candidates who received votes.
3. To calculate the total number of votes each candidate received.
4. To calculate the percentage of votes each candidate won.
5. To determine the winner of the election based on popular vote.
6. To calculate the voter turnout for each county.
7. To calculate the percentage of votes from each county out of the total count.
8. To determine the county with the highest turnout.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.7, Visual Studio Code 1.61.2

## Election-Audit Results:
The analysis of the election show that:
- There were 369,711 votes cast in the election
- The counties included were:
	- Jefferson County
	- Denver County
	- Arapahoe County
- The county with the largest number of votes was Denver county with 306,055 votes.
- The candidates were:
	- Charles Casper Stockham
	- Diana DeGette
	- Raymon Anthony Doane
- The candidate results were:
	- Charles Casper Stockham received 23.0% of the total vote and 85,213 votes.
	- Diana DeGette received 73.8% of the total vote and 272,892 votes.
	- Raymon Anthony Doane received 3.1% of the total vote and 11,606 votes.
- The winner of the election was:
	- Diana DeGette, who received 73.8%" of the total vote and 272,892 votes.

## Election-Audit Summary
By using the python script presented in this analysis we we're able to successfully audit the number of votes for both the candidates and counties involved. 
We were able to determine the winner of the election and we were even able to identify the county with the largest number of votes along with the percentage 
of votes each candidate. The script used demonstrates its automation capability to quickly, and accurately, capture the winner of an election, the total number 
of votes per county, and the county with the largest turnout. We can use this same script with similar datasets for other elections as long as the ballots are
in a list that include the county where that ballot was recorded and the candidate the ballot counts as a vote for. 

We could even modify the script to include other counties that may have been involved with a specific election using .append within its respective list or dictionary. 
We may be able to also include other variables such as voter or candidate party affiliation. If there are multiple elections with candidates on the same ballot, we may even be able to further modify our code similar to how we did to capture county data. We can initialize multiple lists or dictionaries related to those other elections, initialize
additional variables, create code to get information for all ballots, and finally make decision statements based on that voting data.
