# Election_Analysis

 Background
Congratulations! You’ve helped Seth and Tom submit the election audit results to the election commission. But wait! The election commission has requested some additional data to complete the audit:

The voter turnout for each county
The percentage of votes from each county out of the total count
The county with the highest turnout
Working from this module’s election_results.csv file, use for loops and conditional statements with membership and logical operators to find the requested results. Then, print the results to the command line and save them to your election_results.txt file.

Finally, you’ll provide a written analysis of the election audit for the election commission, including the new results and a clearly written overview of your methods. As with all written analyses, this will help your audience understand what you did and what they might be able to do with the data you presented.

What You're Creating
This new assignment consists of two technical analysis deliverables and a written report to deliver your results. You will submit the following:

Deliverable 1: The Election Results Printed to the Command Line
Deliverable 2: The Election Results Saved to a Text File
Deliverable 3: A written Analysis of the Election Audit (README.md)
Files
Use the following link to download the challenge starter code, which includes the Module 3 PyPoll solution.

Download challenge starter codeLinks to an external site.

Instructions
Deliverable 1: Election Results Printed to the Command Line (60 points)
Using repetition statements, conditional statements with logical operators, and print statements, print out the candidate and county election results to the command line.

Download the PyPoll_Challenge_starter_code.py file and rename it PyPoll_Challenge.py.
Use the step-by-step instructions below to add code where indicated by the numbered comments in the starter code file.
Step 1:

Initialize a county list, like the candidate_options list, that will hold the names of the counties.
Initialize a dictionary, like the candidate_votes dictionary, that will hold the county as the key and the votes cast for each county as the values.
Step 2:

Initialize an empty string, like winning_candidate, that will hold the county name for the county with the largest turnout.
Initialize a variable, like the winning_count variable, that will hold the number of votes of the county that had the largest turnout.
Step 3:

While reading the election results from each row inside the for loop, write a script that gets the county name from each row.
Step 4a:

Write a decision statement with a logical operator to check if the county name acquired in Step 3 is in the county list you created in Step 1.
Step 4b:

If the county is not in the list created in Step 1, add it to the list of county names like you did when adding a candidate to the candidate_options list.
Step 4c:

Write a script that initializes the county vote to zero, like you did when you began to track the vote counts for the candidates.
Step 5:

Write a script that adds a vote to the county’s vote count as you are looping through all the rows, like you did for the candidate’s vote count.
Step 6a:

Write a repetition statement to get the county from the county dictionary that was created in Step 1.
Step 6b:

Initialize a variable to hold the county’s votes as they are retrieved from the county votes dictionary.
Step 6c:

Write a script that calculates the county’s votes as a percentage of the total votes.
Step 6d:

Write a print statement that prints the current county, its percentage of the total votes, and its total votes to the command line.
Step 6e: This step will be completed in Deliverable 2.

Step 6f:

Write a decision statement that determines the county with the largest vote count and then adds that county and its vote count to the variables created in Step 2.
Step 7:

Write a print statement that prints out the county with the largest turnout.
After you run your solution to Deliverable 1, confirm that the output to the command line matches the following image:

The election results printed to the computer screen. Line 1 states "Election Results," line 2 contains 25 dashes, line 3 states
"Total Votes: 369,711", line 4 contains 25 dashes, line 5 is blank, line 6 states "County Votes:, line 7 states "Jefferson: 10.5% (38,855)", line 8
states "Denver: 82.8% (306,055)", line 9 states "Arapahoe: 6.7% (24,801)", line 10 is blank, line 11 contains 25 dashes, line 12 states
"Largest County Turnout: Denver", line 13 contains 25 dashes, line 14 is blank, line 15 states "Charles Casper Stockham: 23.0% (85,213," line 16 is blank, line 17 states "Diana DeGette: 73.8% (272,892)," line 17 is blank, line 18 states "Raymon Anthony Doane:
3.1% (11,606)," line 19 is blank, line 20 contains 25 dashes, line 21 states "Winner: Diane DeGette," line 22 states "Winning Vote Count: 272,892," line 23 states "Winning Percentage: 73.8%," line 24 contains 25 dashes.

Deliverable 2: Election Results Saved to a Text File (20 points)
Using your knowledge of writing data to a text file, write the winning candidate results and the county election results to the election_results.txt file.

Use the step-by-step instructions below to add code where indicated by the numbered comments in the starter code file.

Step 6e:

Write a script that saves each county, the county’s total votes, and the county’s percentage of total votes to the election_results.txt file.
Step 8:

Write a script that saves the county with the largest turnout to the election_results.txt file.
After you run your solution to Deliverable 2, confirm that your election_results.txt file matches the following image:



Deliverable 3: Written Analysis of the Election Audit (20 points)
Use your repository README to write your analysis of Deliverables 1 and 2. The analysis should contain the following:

Overview of Election Audit: Explain the purpose of this election audit analysis.

Election-Audit Results: Using a bulleted list, address the following election outcomes. Use images or examples of your code as support where necessary.

How many votes were cast in this congressional election?
Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
Which county had the largest number of votes?
Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.
