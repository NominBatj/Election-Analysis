# Election Analysis
## Overview of Project
The purpose of the project is to analyze election audit of local congressional election in Colorado using programming tools: Python and Visual Studio Code and submit the result to election commision.
## Election Audit Results 
The Electoral Commission requested additional analysis of the election data. Voter turnout count questions for each county that voted in the constituency. How to calculate the percentage of votes cast by each constituency in an election. We also were asked to determine which district had the largest turnout.
We created a python script where we performed calculations on the counts, used loops and if-conditional statements to make a report to our analysis.

![for loops](https://user-images.githubusercontent.com/66500222/168440982-745579f0-5f15-4296-b6af-d02f11c3fb20.png)


As a result we can answer following questions:
- How many votes were cast in this congressional election?

Total Votes: 369,711
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

County Votes:
Jefferson: 10.5% (38,855)

Denver: 82.8% (306,055)

Arapahoe: 6.7% (24,801)
- Which county had the largest number of votes?

Denver
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

Charles Casper Stockham: 23.0% (85,213)

Diana DeGette: 73.8% (272,892)

Raymon Anthony Doane: 3.1% (11,606)

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

Winner: Diana DeGette

Winning Vote Count: 272,892

Winning Percentage: 73.8%

Here is the output of the code:

![Result in visual studio](https://user-images.githubusercontent.com/66500222/168441033-2520a586-ff1b-43ee-8213-7d7bb182f3f7.png)


## Election Audit Summary
Using loops and decision operators, the script looks up how many candidates got, how many votes, percentages and calculates who won by printing these results to a text file.This script can be modified and used in all levels of elections, for example, if we analyze the presidential elections, we probably will need to extend the dataset and will most likely include state data as well as county data, so there will be a whole different column for states. The analysis of presidential elections may also require an Electoral College data set. We can use if-statements in scenario where once a county received many popular votes, it would automatically need to be assigned electoral college votes. Also, we can use script to determine a rank of candidates by preference on their ballots. If the candidate receives a majority of the first preference votes, he or she is declared the winner. If no candidate receives a majority of first preference votes, the candidate with the fewest first preference votes is eliminated. First preference votes cast for a failed candidate are eliminated and the second preference votes listed on those ballots are cancelled. A new count is made to determine if any candidate has won the majority of the adjusted votes. The process is repeated until the candidate wins an absolute majority.
