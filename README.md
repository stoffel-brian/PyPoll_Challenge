# PyPoll_Challenge


## Overview of Election Audit. 

The purpose of this election audit was to automate the summation of the election results by candidate and county. Additionally, the percentage of votes won per candidate, the turnout per county, and the election winner were also calculated. 

[PyPoll_Challenge (.py)](/../main/PyPoll_Challenge.py)




## Election-Audit Results


[Election_Analysis (.txt)](/../main/election_analysis.txt)

- How many votes were cast in this congressional election?
369,711 votes were casted in this congressional election.

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
County Votes:
Jefferson: 10.5%  (38,855)
Denver: 82.8%  (306,055)
Arapahoe: 6.7%  (24,801)

- Which county had the largest number of votes?
Denver County

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
Candidate Votes:
Charles Casper Stockham: 23.0% (85,213)
Diana DeGette: 73.8% (272,892)
Raymon Anthony Doane: 3.1% (11,606)

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
Diana DeGette
Vote Countt: 272,892
Percentage Votes: 73.8%


## Election-Audit Summary


This script can be used for any election with a few modifications and inherent cost savings. The input file (election_results.csv) will need to be updated with the correct election data or modification to re-route the script to connect to a new file containing the election data. Another example of modifying the script would be to add-in lines for the turnout per county, the largest county turnout count, and the highest county turnout percentage. These modifications are commentted in the script but can be implemented as a modification for future or other election data requirements. 
