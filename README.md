#   Election_Analysis - This report summarizes an election audit for a Colorado election

##  Election Details

- Colorado voters from Jefferson, Denver, and Arapahoe Counties participated in this election.
- The 3 candidate for election were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
  
##  Audit Process

  - The total number of votes cast in the election were calculated.
  - The number of votes cast by voters from Jefferson, Denver, and Arapahoe counties were calculated.
  - The percentage of votes cast by voters from Jefferson, Denver, and Arapahoe counties were calculated.
  - The county that delivered the highest number and percentage of votes was determined.
  - The number of votes and the percentage of votes cast for the 3 candidates were calculated.
  - The winning candidate was determined. 

##  Summary

  - Total Votes: 369,711
  - Jefferson County: 10.5% (38,855 votes)
  - Denver County: 82.8% (305,055 votes)
  - Arapahoe County: 6.7% (24,801 votes)
  - Largest County Turnout: Denver

  - Charles Casper Stockham: 23.0% (85,213 votes)
  - Diana DeGette: 73.8% (272,892 votes)
  - Raymon Anthony Doane: 3.1% (11,606 votes)
  - Winner: Diana Degette

## PyPoll_Challenge.py

  - Total votes, ID of counties, county votes, ID of candidates, and candidate votes calculed in "for" loop starting at Line 51.
  - Winning county county determined in "for" loop starting at line 107.
  - Formatting for county command line output and txt.file output in "for" loop starting at line 107.
  - Winning candidate determined in "for" loop starting at line 145. 
  - Formatting for candidate command line output and txt.file output in "for" loop starting at line 145.

## Potential uses for PyPoll_Challenge.py script in other election audits
  - PyPoll_Challenge.py script could be used to audit other elections provided input file is in same format as this input.
  - PyPoll_Challenge.py script could be refactored by changing indexes in lines 57 & 60 to account for column changes for county and candidate data.

## Screen shots

![command line screen shot](/Resources/Module_3-challenge_command-line-output.png)
![txt.file screen shot](/Resources/Module_3-challenge_election_results.txt.png)





