# Election_Challenge
## Overview of Election Audit
A Colorado Board of Elections employee has tasked us to complete the election audit of a recent local congressional election. We are to deliver the following:

1. Total number of votes cast.
2. A complete list of candidates who received votes.
3. The total number of votes each candidate received.
4. The percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. A complete list of participating counties.
7. The voter turnout for each county.
8. The percentage of votes from each county.
9. Determine the county with the highest turnout.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.7, Visual Studio Code 1.63.2

## Election-Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The number of votes and percentage of votes based on county were:
    - Arapahoe: 6.7% (24,801)
    - Denver: 82.8% (306,055)
    - Jefferson: 10.5% (38,855)
- The county with the largest voter turnout was:
    - Denver
- The candidate results were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes
    - Diana DeGette received 73.8% of the vote and 272,892 number of votes
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote and 272,892 number of votes

## Election-Audit Summary
The program to process the election results from the election_results.csv file completes the task of outputting the results in a concise logical manner. However, there is potential to modify the program to allow the program to process results from any election. Two modifications come to mind. One is to add an option to specify the file path of any raw election results data provided that the data is formatted prior to running the program. The second is to change the output results to general descriptions to allow for use in other word processing programs for distribution to print media or online websites.
