# Election_Analysis
Analyzing election data with Python

## Overview of Election Audit
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.9.10, Visual Studio Code, 1.65.2

## Election-Audit Results

The analysis of the election show that:

- There were 369,711 votes cast in the election.
- The county results were:
    - Jefferson county received 38,855 number of votes and 10.5% of the total votes.
    - Denver county received 306,055 number of votes and 82.8% of the total votes.
    - Arapahoe county received 24,801 number of votes and 6.7% of the total votes.
- The county with largest number of votes was:
    - Denver
- The candidates were:
    - Charles Casper Stockham
    - Diana DeGette
    - Raymond Anthony Doane
- The candidate reults were:
    - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
    - Diana DeGette received 73.8% of the vote and 272,892 votes.
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
- The winner of the election was:
    - Diana Degette, who received 73.8% of the vote and 272,892 number of votes.

![image](https://user-images.githubusercontent.com/100643519/160257729-9731882a-e32e-44ba-b81a-d7198aa8fd28.png)

## Election-Audit Summary

This script can be used to audit the results of any election as long as you are provided a csv file with the election results. You could modify the script to audit a different congressional election by changing the file and path referenced by the file_to_load variable. You could also modify the script to get the popular vote results for a national election. You would need a csv file with the election results. You would need to modify the path and file referenced by the file_to_load variable. You could modify the county results to count state results.