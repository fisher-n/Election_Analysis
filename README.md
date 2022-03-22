# Election_Analysis

## Project Overview
Election audit of recent local congessional election for Colorado Board of Elections employee

1. Calculate the total number of votes cast
2. Get a complete list of candidates who recieved votes.
3. Calculate the total number of votes
4. Calculate the precentage of votes each candidate won.
5. Determind the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary
The analysis of the election show that: 
- There were 369,711 votes cast in the election
- The candidates were
    - Charles Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
-The candidate results were:
    - Charles Casper Stockham recieved 23.0% of the vote and 85,213 of the votes.
    - Diana DeGette reciveced 73.8% of the votes and 272,892 of the votes.
    - Raymon Anthony Doane recieved 3.1% of the votes and 11,606 of the votes.
- The winner of the election was:
    - Diana DeGette reciveced 73.8% of the votes and 272,892 of the votes.

# Challenge Overview 
The inital analysis provided answers but left unanswered questions, Seth, the Colorado Board of Elections employee requested a deeper written analysis using VS Code and saving the results to a [text file](https://github.com/fisher-n/Election_Analysis/blob/main/analysis/election_analysis.txt) for later reference. 

## Election-Audit Results
   - There were 369,711 total number of votes cast.
   
   - County Votes:
        - Jefferson county cast 10.5% of the votes and 38,855 of the votes
        - Denver county cast 82.8% of the votes and 306,055 of the votes.
        - Arapahoe county cast 6.7% of the votes and 24,801 if the votes.
   - Denver county had the largest number of votes.
   - The candidate results were:
        - Charles Casper Stockham recieved 23.0% of the vote and 85,213 of the votes.
        - Diana DeGette reciveced 73.8% of the votes and 272,892 of the votes.
        - Raymon Anthony Doane recieved 3.1% of the votes and 11,606 of the votes.
    - The winner of the election was:
        - Diana DeGette reciveced 73.8% of the votes and 272,892 of the votes. 

Print out of findings:
![This is an image](https://github.com/fisher-n/Election_Analysis/blob/main/Resources/Deliverable_1.png)


## Election-Audit Summary
This election audit script can be easily modifided for any election given a CSV file. One would only have to add the CSV file to a folder and edit the file_to_load in the script. One could also change the name of the file_to_save if they wanted to use a different file name or already had an analysis folder.
