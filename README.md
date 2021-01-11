# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election. 

1. Calculate the total number of votes cast. 
2. Get a complete list of candidates who recieved votes. 
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won. 
5. Determine the winner of the election based on popular vote. 

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary 
The analysis of the election show that: 
- There were 369,711 votes cast in the election. 
- The candidates were: Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane.
 - The candidate results were: 
    
            Charles Casper Stockham received 23.0% of the vote and 85,213 number of votes. 

            Diana DeGette received 73.8% of the vote and 272,892 number of votes. 

            Raymon Anthony Doane received 3.1% of the vote and 11,606 number of votes. 
  - The winner of the election was Diana DeGette, who received 73.8% of the vote and 272,892 number of votes. 
  
![alt text](https://github.com/kmfriesen/Election_Analysis/blob/main/Resources/Election_results_candidates.PNG)
    
## Challenge Overview
The purpose of this election audit analysis was to determine the voter turnout for each county, the percentage of votes from each county out of the total count, as well as    find out which county had the highest turnout. 
## Challenge Summary 
- The counties were: Jefferson, Denver, and Arapahoe. 

- The percentage of votes coming from these counties are: 
            Jefferson: 10.5% (38,855)
            Denver: 82.8% (306,055)
            Arapahoe: 6.7% (24,801)
            
![alt text](https://github.com/kmfriesen/Election_Analysis/blob/main/Resources/Election_results.PNG)

- The largest county turnout was in Denver with 82.8% of the votes and 306,055 number of votes.  

### Business proposal
This script can be used with some modifications for auditing any election in the future. You can change the file you use to pull data and therefore change all the information related where the votes came from (like the county name in this example), candidate names (can be any number), and the number of votes for that election aggregated by candidate and county or any other variable presented in the csv data file. 
In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.
