# Pewlett-Hackard-Analysis
Perform a thorough employee research analysis in order to prepare Pewlett-Hackard for many upcoming retirements that will lead to thousands vacancies throughout the entire company.  This analysis will prepare Bobby's manager with a accurate data of all the upcoming retirees within the company.
## Results
#### To retrieve all the employees who were born between 1/1/1952 - 12/31/1955, with all their held titles; the emp_no, first_name, and last name columns are retrieved from the Employees table and title, from_date, and to_date columns are retrieved from the Titles table.
#### In order to get all the titles of the employees who were born between 1952-1955, the DISTINCT ON statement is used to get the most recent title of employees as shown below, a snippet:
####<img width="336" alt="Screen Shot 2022-04-07 at 8 41 57 PM" src="https://user-images.githubusercontent.com/99656224/162341297-6c5136ad-d285-456c-9a50-8cb5e75da3be.png">
#### To retrieve the final number of employees retiring by their most recent held job title, data was collected from the Unique Titles table and put into a new Retiring Titles table. A snippet of the code used is shown below:
#### <img width="269" alt="Screen Shot 2022-04-07 at 8 57 51 PM" src="https://user-images.githubusercontent.com/99656224/162342655-0d19d8dc-7c1a-4be6-9272-68d80271f628.png">
#### Lastly, a mentorship table was created with the current employees who were born between 1/1/1965  - 12/31/1965 by using the code below:
#### <img width="458" alt="Screen Shot 2022-04-07 at 9 00 54 PM" src="https://user-images.githubusercontent.com/99656224/162342906-78db6439-1959-4f4a-b240-fcd3af50bf58.png">
## Summary
#### In accordance to the tables generated, a total of 90,368 people will be retiring leaving room for thousands of new employees.  There might not be enough people to fill these positions as quickly as Pewlett-Hackard would like, but they should take advantage of the mentorship program set in place.
