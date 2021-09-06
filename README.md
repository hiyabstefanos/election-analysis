# Election Analysis

## Overview of Election Audit: 

We have been given a dataset from the Colorado Board of Elections to analyze and deliver the results of the election by looking at:
Total number of votes cast
A complete list of candidates who received votes
Total number of votes each candidate received
Percentage of votes each candidate won
The winner of the election based on popular vote


## Election-Audit Results

- How many votes were cast in this congressional election?
  - 369,711
- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
- Which county had the largest number of votes?
  - Denver
- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received
  -  Charles Casper Stockham: 23.0% (85,213)
  -  Raymon Anthony Doane: 3.1% (11,606)
  -  Diana DeGette: 73.8% (272,892)
- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  - Winner: Diana DeGette
  - Winning Vote Count: 272,892
  - Winning Percentage: 73.8%
  
## Election-Audit Summary
The great thing about a script like this is that with minimal modifications, it can be used in any election - with a few modifications. 
<img width="376" alt="Screenshot 2021-09-05 235228" src="https://user-images.githubusercontent.com/89358080/132158419-f03ac572-388f-4b96-a209-353cb9fb1f43.png">

Here, the code can be modified to adjust the file that will be loaded by simply changing the file path. As long as the data provided follows the headers provided in the proper csv or txt format.
Second, the amount of votes needed to win could be adjusted.
<img width="337" alt="2" src="https://user-images.githubusercontent.com/89358080/132158799-8081e196-58c2-4b9a-b02a-960c2e36d770.png">
