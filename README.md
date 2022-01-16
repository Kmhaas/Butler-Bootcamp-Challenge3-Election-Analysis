# Election Analysis Challenge

## Overview of Election-Audit 
A Colorado Board of Elections employee has given myself the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who recieved votes.
3. Calculate the total number of votes each candidate recieved.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Caluluate voter turnout for each county.
7. Calculate the percentage of votes from each county out of the total vote count.
8. Calculate the county with the highest voter turnout.

## Resources
- Data Source: election_resulys.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Election-Audit Results
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The county vote results were:
  - Jefferson recieved 10.5% of the votes and 38,855 number of votes.
  - Denver recieved 82.8% of the votes and 306,055 number of votes.
  - Arapahoe recieved 6.7% of the votes and 24,801 number of votes.
- The county with the largest number of votes was:
  - Denver (82.8%, 306,055 votes)
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham recieved 23.0% of the votes and 85,213 number of votes.
  - Diana DeGette recieved 73.8% of the votes and 272,892 number of votes.
  - Raymon Anthony Doane recieved 3.1% of the votes and 11,606 number of votes.
- The winner of the election was:
  - Candidate Diana DeGette, who recieved 73.8% of the vote and 272,892 number of votes.



  ![Election-audit results](https://user-images.githubusercontent.com/93004710/149649073-358d7b28-5a86-44ea-8970-cf659e1345d0.png)



## Election-Audit Summary
I propose the election commission continues to use this script for future elections with modifications to provide results like the ones shown with the script:
  - Modifying the script with the key and value figures to will correctly input dictionairies and lists populating new results.
  - Modifying the row index numbers incase new csv forms add new colunms, the column number would have to be modified to reflect so. For example, if changes are made to the original cvs file as having county being the first colunm in the set instead of having county name be [1] it would be [0].


