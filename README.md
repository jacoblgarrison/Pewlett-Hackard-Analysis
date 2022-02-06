# Pewlett-Hackard-Analysis

## Overview
The purpose of this analysis was to take a look at the Pewlett-Hackard company and give insight to the amount of people nearing or at retirement. On top of that, we wanted to see how many employees would be near retirement and eligible for a part-time mentorship program to assist with the upcoming "silver tsunami". 

## Results 

* Our first deliverable combines the 'employee' table along with data from our 'titles' table. This shows us all employees and their respective title that were born between 1952 and 1955 that could be eligible for the mentorship program.

![Screen Shot 2022-02-06 at 3 01 05 PM](https://user-images.githubusercontent.com/95515322/152701210-9703aa5b-b4c1-4cf0-a1a8-4fcb102b0a56.png)


* After fine-tuning this data some more, we eliminate any duplicate rows and find there are over 72,000 employees still with the company that were born between 1952 and 1955. We put this into a new table called 'unique_titles' to distinguish it from our earlier data.

![Screen Shot 2022-02-06 at 2 56 01 PM](https://user-images.githubusercontent.com/95515322/152701242-fb73e092-c04c-40eb-bd80-37136e774f8a.png)

* When combing through unique_titles some more, I see there are 50,842 employees that have 'Senior' in their title. 

* The final task of our project shows us data in our table that is very beneficial to our potential mentorship program. With the mentorship_eligibility table we can see the title of employees and how long they've been with the company.

![Screen Shot 2022-02-06 at 3 20 19 PM](https://user-images.githubusercontent.com/95515322/152701837-a1ba78b4-09cb-4a70-8862-530c1b4a2e54.png)

## Summary
When looking at the unique_titles table, there are 72,459 employees still with the company that were born between 1952 and 1955 that will need replacements soon.

Seeing that there are only 1,549 employees that appear to have mentorship eligibility. This shows there is a large gulf in the amount of workers set to retire and the amount of workers that could take on a mentorship role. To help bridge this gap, Pewlett-Hackard could try hiring outside the company to help fill these roles as opposed to only promoting from within.
