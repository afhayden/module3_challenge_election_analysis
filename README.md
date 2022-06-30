# Colorado Election Audit Analysis

## Overview of Election Audit Reporting Requirements
A Colorado Board of Elections has provided election voting data to complete an audit of a recent local congressional election.

1. Calculate the total number of votes cast per candidate and per county.
2. Obtain a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the total number of votes cast per county.
5. Calculate the percentage of votes each candidate won.
6. Calculate the percentage of votes cast per county.
7. Determine the winner of the lection based on popular vote.
8. Determine the county with the largest voter turnout.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary of Election Audit Results
The analysis of the election show that:
- There were "396,711" votes cast in the election.

- The candidates were:
  - Candidate Charles Casper Stockham
  - Candidate Diana DeGette
  - Candidate Raymon Anthony Doane

- The candidate results were:
  - Candidate Charles Casper Stockham received "23.0%" of the vote and "85,213" number of votes.
  - Candidate Diana DeGette received "73.8%" of the vote and "272,892" number of votes.
  - Candidate Raymon Anthony Doane received "3.1%" of the vote and "11,606" number of votes.
 
 - The winner of the election was:
    - Candidate Diana DeGette, who received "73.8%" of the vote and "272,892" number of votes.
 
 - The county vote results were:
    - Jefferson county casts "10.5%" of the votes and "38,855" number of votes.
    - Denver county casts "82.8%" of the votes and "306,055" number of votes.
    - Arapahoe county casts "6.7%" of the votes and "24,801" number of votes.
    - The county with the largest voter turnout was Denver.
  
 ## Future Election Audit Code Reuse Recommendations
 This current code base can be further enhanced to provide more data analysis. Two (2) recommended examples are as follows:
 
 - Recommendation #1: Identify the popularity of each candidate per county.
    - Expand the county_votes dictionary include a counter for each candidate per county
    - Loop through the csv file again and add up the votes

- Recommendation #2: Yearly comparison of county data
    - If county data for previous years can be provided, we can identify wither voter turnout has improved and for which counties
