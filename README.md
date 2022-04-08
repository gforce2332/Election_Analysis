# Election_Analysis
Click here to view the Python file: [Election Analysis](https://github.com/gforce2332/election_analysis/blob/main/PyPoll_Challenge.py)


## Table of Contents
* [Election Audit Overview](#election_audit_overview)
* [Resources](#resources)
* [Results](#results)
* [Screenshots](#screenshots)
* [Summary](#summary)


## Election Audit Overview
Assisted the Colorado Board of Elections in an election audit for the US Congressional precinct in a recent election. The following tasks were requested for reporting results:

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes for each candidate.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on the popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.66.0

## Results
The analysis of this election shows that:
- There were 369,711 votes cast in the election.
- The number of votes received for each county in the precinct were:
     - Jefferson County received 10.5% of the vote and 38,855 number of votes.
     - Denver County received 82.8% of the vote and 306,055 number of votes.
     - Arapahoe County received 6.7% of the vote and 24,801 number of votes.
- The county with the largest number of votes was:
     - Denver County which received 82.8% of the vote and 306,055 number of votes.
- The candidates were:
     - Charles Casper Stockham
     - Diana DeGette
     - Raymon Anthony Doane
- The candidate results were:
     - Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
     - Diana DeGette received 73.8% of the vote and 272,892 number of votes.
     - Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
- The winner of the election was:
     - Diana DeGette who received 73.8% of the vote and 272,892 number of votes. 

## Screenshots
![election_results](https://user-images.githubusercontent.com/98711219/162375190-4b7b98da-f70d-4662-95c4-8b6a01210900.png)


## Summary
This script can be used not only to audit this election but other congressional, senate 
and local elections as well. If the data were to include other characteristics, such as 
demographics and geography, the script can be modified to include these characteristics
and the analysis can be broken down even further.

This script can be further  modified to determine patterns among the characteristics. We could 
analyze the percentage of voters by county against each candidate. This would allow us to see 
which candidate was the most popular within a county or geographical area.
