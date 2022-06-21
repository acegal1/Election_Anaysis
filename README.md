# Election_Anaysis
# Overview of Project Election Audit
A Colorado Board of Elections employee has requested an election audit of a U.S. Congressional District tabulated results. The following tasks are required to complete the election audit:

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes for each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Determine the county with the highest turnout.
7. Calculate the percentage of votes from each county out of the total.

# Resources
    - Software: Python 3.9.12
    - Data Source: election_results.csv

## Deliverable 1 Analysis
The election commission has requested some additional data to complete the audit so we upadated our PyPoll code as per below requirements:

    -Total Votes in the election are printed to the terminal.
    -Each candidate’s total votes and percentage of votes are printed to the terminal.
    -The winner of the election, winning vote count, and winning percentage of votes are printed to the terminal.

Here is a view updated code image:
![Deliverable_1]((https://github.com/acegal1/Election_Anaysis/blob/main/Resources/Deliverable_1.png)

## Deliverable 2 Analysis

In this deliverable we need to write data to a text file, write the winning candidate results and then county election results text file to be saved following data.

- Each county and its total vote count 

- Each county and its percentage of the total votes 

- The county with the largest number of voters 

 Updated code Shown as below :

![Deliverable 2a updated code](https://github.com/acegal1/Election_Anaysis/blob/main/Resources/Deliverable_2a.png)

![Deliverable 2b updated code](https://github.com/acegal1/Election_Anaysis/blob/main/Resources/Deliverable_2b.png)

# Election-Audit Results

As per above analysis of the election results shows that:

- There were 369,711 votes cast in the election.

The candidates were:

- Charles Casper Stockham

- Diana DeGette

- Raymon Anthony Doane

The candidate results were:

- Charles Casper Stockham received 23.0% of the vote, for a total of 85,213 votes.

- Diana DeGette received 73.8% of the vote, for a total of 272,892 votes.

- Raymon Anthony Doane received 3.1% of the vote, for a total of 11,606 votes.

               
The winner of the election was:

- Diana DeGette, who received 73.8% of the vote for a total of 272,892 votes.

The voter turnout for each county was:

- Jefferson produced 10.5% of voters, for a total of 38,855 voters.

- Denver produced 82.8% of voters, for a total of 306,055 voters.

- Arapahoe produced 6.7% of voters, for a total of 24,801 voters.

The county with the largest voter turnout was:

- Denver, which produced 82.8% of voters, for a total of 306,055 voters.

And our final election_result Shown as below:

![Election_final result](https://github.com/acegal1/Election_Anaysis/blob/main/Resources/Election_final.png)


# Election-Audit Summary
Original audit python program code provided total number of votes cast, calculate the number and the percentage of votes for each of the candidates to determine the winner.   

The updated code provided the ability to tally votes counts to produce data on voter turnout for each county, percentage of votes for each county out of total count and the county with the highest turnout. won by each county and by candidate.  

Expanding the Election Audit program code to include voter turnout by county then by candidates results displays how coding enables you to achieve more with less.  Modifications to code can be done quickly and did drastically reduces the number of hours spent on development. The initial investment of creating a python program to tally votes and provide additional on-demand data analysis can be re-used for future elections.  You have to agree definitly cost effective.  


Modifying the script to produce turnout results by county is just one of many ways that minor adjustments to the code can reveal critical data. By simply adding an if-statment to the code, we were able to determine what percentage of each county voted for each candidate. These type of Decision Statements are how the code runs calculations and it was provided with the data file.

Finally the modified script used to perform the Election Audit can be a valuable resourse for the election board that provided valuable insights for future elections. If we could include additional demographic data by county you could allocate resources to low turnout counties. 