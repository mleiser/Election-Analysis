# Election-Analysis

## Overview of Election Audit
  
### Purpose
  The purpose of this election audit analysis is to provide the election commission with asked for data.  This data includes: 
  -Voter turnout for each county
  -The percentage of votes from each county of the total count
  -The county with the highest voter turnout
  Using this data, we hope to assist the election commission in their endeavors.

## Election Audit Results
- The total number of votes was 369,711 votes.
- Jefferson county had 10.5% of the votes at 38,855 votes, Denver county had 82.8% of the votes at 306,055 votes, and Arapahoe had 6.7% of the votes at 24,801 votes
- The County with the largest number of votes was Denver county with 306,055 votes
- Charles Casper Stockham had 23.0% of the votes at 85,213 votes, Diana DeGette had 73.8% of the votes at 272,892 votes, and Raymon Anthony Doane had 3.1% of the votes at 11,606 votes
- Diana DeGette won the election with 73.8% of the vote at 272,892 votes in total.

## Election Audit Summary
 It's important to note that the script used for this election audit is versitile enough to be used in any election in the future.  For example, the code that's used to track the candidate names and vote totals can be changed to accommodate candidates of whatever election is being done.  The only thing that needs be changed for that is to change the code below
 ```
 with open(file_to_load) as election_data:
    reader = csv.reader(election_data)
 ```
to whatever file is holding the election data.  The scripts can also be changed in a way to keep track of states rather than counties by changing the county code into storing state names rather than just counties.
