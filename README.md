# Election_Analysis

## Overview of Election Audit
Seth and Tom, Colorado Board of Elections employees, gave me the following tasks to complete the election audit of a recent local congressional election.

1.  Calculate the total number of votes cast.
2.  Get a complete list of candidates who received votes.
3.  Calculate the total number of votes each candidate received.
4.  Calculate the percentage of votes each candidate won.
5.  Determined the winner of the election based on the popular vote.
6.  Calculate the number of votes and percentage of votes in each county.
7.  Determine which county had the largest turnout.

## Resources
-Data source: elections_results.csv
-Software: Python 3.6.7, Visual Studio Code 

## Election-Audit Results
*There were 369,711 votes cast in the election.

*The counties in this audit, their percentage of total votes and total votes:
    -Jefferson: 10.5% (38,855)
    -Denver: 82.8% (306,055)
    -Arapahoe: 6.7% (24,801)
    
*The county with the largest voter turnout was Denver.

*The candidates were:
    -Charles Casper Stockham
    -Diana DeGette
    -Raymon Anthony Doane
    
*The candidates results were:
    -Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes.
    -Diana DeGette received 73.8% of the vote and 272,892 number of votes.
    -Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes.
    
*The winner was Diana DeGette with 73.8% of the vote and 272,892 number of votes.

## Election-Audit Summary
Going forward this script can be used on future elections with only a few modifications.

The file_to_load path may need to be adjusted for the new dataset. (lines 6 & 8)
The candidate_name list number and the county_name list number may need to be changed depending on the configuration of the columns of the new dataset. (lines 46 & 49)
-


    -



