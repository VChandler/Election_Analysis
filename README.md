# Election Analysis

## Project Overview
The project, commissioned by the Board of Elections, is to audit the numbers around a recent congressional election.  Tasks include:  

1. Calculate the total number of votes cast.
2. Calculate the number of counties, the votes per counties, and the percentage of overall votes per county.
3. Identify the county with the largest voter turnout.
4. Calculate the vote count for each candidate.
5. Calculate the percentage of overall votes for each candidate.
6. Identify the winning candidate of the election via the highest number of votes received.

## Election-Audit Results
Election output:  
![Screenshot 2021-08-30 214009](https://user-images.githubusercontent.com/88070999/131432918-43db3120-4b7a-4e25-9a20-19851106a8ad.png)

* How many votes were cast in this congressional election?  
  A total of 369,711 votes were cast in the election.
  
* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.  
  * Jefferson: 10.5% (38,855)
  * Denver: 82.8% (306,055)
  * Arapahoe: 6.7% (24,801)
  
* Which county had the largest number of votes?  
  Denver had the highest number of votes by far (306,055), which accounted for 82.8% of the total votes cast.
  
* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.  
  * Charles Casper Stockham: 23.0% (85,213)
  * Diana DeGette: 73.8% (272,892)
  * Raymon Anthony Doane: 3.1% (11,606)

* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?  
  Diana DeGette was the winning candidate.  She garnered 272,892 total votes, which was 73.8% of all votes received.

## Election-Audit Summary
With the completion of this project, the code can be easily modified for use with other elections.  For example:
* By modifying the code related to counties, the program can be changed to allow for smaller scale elections.  School board elections, county councils, and others can all be tracked by towns, municipalities, or whatever territories are identified.
* The code relating to "candidates" can also be very easily modified to track propositions, amendments, or whatever other issue might be on the ballot.

In addition to the benefits above, the code is written in a way that self-adjusts for the number of candidates and counties without any modifications whatsoever.  For elections with 10 candidates or 7 counties (as an example), no coding changes are necessary- the election results will expand or contract as necessary to accommodate the raw data.
