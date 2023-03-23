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
![image](https://user-images.githubusercontent.com/119356389/227345365-69584874-6aff-46d0-b3b4-98f4e3007ed7.png)



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

    There were 369,711 votes that were cast in this election. 
    ![image](https://user-images.githubusercontent.com/119356389/227346097-b87b3268-cc9d-4dff-9318-5432ca289abf.png)

    
    
Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  The following is a breakdown of the votes for each county : 
  ![image](https://user-images.githubusercontent.com/119356389/227346495-1944ee36-923b-4447-956c-c090ce0c23d3.png)

  
Which county had the largest number of votes? 
  Denver is the county with the largest number of votes: 
  ![image](https://user-images.githubusercontent.com/119356389/227346954-7d2ccf7e-9b85-4707-8ad3-90f221f618be.png)

  
Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
 The following is the breakdown of the total votes for each condidate: 
 ![image](https://user-images.githubusercontent.com/119356389/227347412-097595e0-f94c-48ee-a159-587c40987ca6.png)

Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  The winner of the election is Diana DeGette with 272,892. This was 73.8% of the total votes. 
  ![image](https://user-images.githubusercontent.com/119356389/227348116-42f83f59-a0dc-4305-b625-11a8ac1d50cb.png)

 
Election-Audit Summary: This is an template that can help with elections at any level of government or for anything issue that needs a consensus. I would modify the script to look at issues, and towns, specific cities where councilmen are elected. Where ever there is readable data you can use this scrript to put together the outcomes. 
