# Election_Analysis_2022

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete llist of candidates who received votes.
3. Calculate the total number of votes each candidate receieved.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.1, Visual Studio Code, 1.38.1

## Summary 
The analysis of the election show that:
- There were "369,711" votes cast in the election.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were: 
  - Charles Casper Stockham receieved "23.0%" of the vote "85,213" number of votes.
  - Diana DeGette: "73.8%" of the vote and "272,892" number of votes. 
  - Raymon Anthony Doane: "3.1%" of the vote "11,606" number of votes. 

## Overview of Election Audit
The purpose of this Election Audit is to show the tally of how many total votes were casted by three counties in Colorado. This analysis also shows the number of votes each county received. Each of these three counties votes percentages were calculated by taking the total number of votes per county divided by the total votes all together times 100. Along with the number of votes and percentages that each candidate received the Winner of the campaignis displayed in the text file. It can be infered from these results that most of Diana DeGette's votes came from those who reside in Denver County. 
## Election-Audit Results
  1. How many votes were cast in this congressional election?
  - The total number of votes for this election were 369,711. The variable "total_votes" is initialized at the beginning of the code to store the count of each vote. 
<img width="534" alt="Screen Shot 2022-01-22 at 7 13 25 PM" src="https://user-images.githubusercontent.com/77857472/150659647-430d6057-066c-427c-acc7-ef9c6e42b74f.png">
<img width="534" alt="Screen Shot 2022-01-22 at 7 13 15 PM" src="https://user-images.githubusercontent.com/77857472/150659663-8659c58d-2d92-457a-b219-b5c55757ccd8.png">

  2. Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  - To find the number of votes for each county a a for loop is created to loop through the election results file.
  <img width="817" alt="Screen Shot 2022-01-22 at 7 48 38 PM" src="https://user-images.githubusercontent.com/77857472/150660290-bbbcf366-fb7a-4acb-b739-996624897628.png">
  - The number of votes for each county were displayed in the text file attached below.
  <img width="242" alt="Screen Shot 2022-01-22 at 7 50 15 PM" src="https://user-images.githubusercontent.com/77857472/150660314-507779cb-9404-4cfb-b238-7f4daeb9988d.png">
  3. Which county had the largest number of votes?
  - The county with the largest number of votes was Denver County with 306,055 votes which accounts for the 82.8% of total votes of the entire campaign. 
  4. Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
  - Charles Casper Stockham received 85,213 votes which is 23% of total votes from the election. 
  - Raymon Anthony Doanne received 11,606 votes 3.1% of total votes.
  - Diana DeGette who is the obvious winner of the election received 272,892 votes which equates to 73.8% of the votes for the election. 
  5. Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  - Diana DeGetter won the election. Her voter count was 272,892 votes and her percentage of total votes was 73.8% which is about 3/4 of all total votes.

## Election-Audit Summary
