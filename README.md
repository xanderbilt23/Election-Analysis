# Election-Analysis

## Project Overview

A Colorado Board of Elections employee has given the following tasks to complete the election audit of a recent congressional election.

1. Calculate the total number of votes cast.
2. Calculate the number of votes for each county in the precinct.
3. Calculate the percentage of total votes for each county in the precinct.
4. Determine which county had the largest number of votes.
5. Get a complete list of candidates who received votes.
6. Calculate the total number of votes each candidate received.
7. Calculate the percentage of votes each candidate won.
8. Determine the winner of the election based on popular votes.

## Resources

- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.68.1

## Results

The analysis of the election show that:

- There were 369,711 votes cast in the election.
- County votes were:
  - Jefferson county received 10.5% of the votes and 38,855 number of votes.
  - Denver county received 82.8% of the votes and 306,055 number of votes.
  - Arapahoe county received 6.7% of the votes and 24,801 number of votes.

The following code was used to calculate the percentage of total votes for each county:

```python

county_vote_percentage = float(C_votes) /float(total_votes)\* 100
```

- The county with the largest turnout was:
  - Denver county, which received received 82.8% of the votes and 306,055 number of votes.
- The candidates were:
  - Charles Casper Stockham:
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the votes and 85,213 number of votes.
  - Diana DeGette received 73.8% of the votes and 272,892 number of votes.
  - Raymon Anthony Doane received 3.1% of the votes and 11,606 number of votes.
- The winner of the election was:
  - Diana DeGette, who received 272,892 number of votes 73.8% of the total votes.

![election_analysis](https://github.com/xanderbilt23/Election-Analysis/blob/main/Resources/election_analysis.png)

## Election-Audit Summary

This script can be used for any election by changing the file to load and the file to save file path.
