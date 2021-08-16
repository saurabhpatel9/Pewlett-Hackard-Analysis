# Pewlett-Hackard-Analysis


## Overview & Purpose
The purpose of our analysis is to find out the number of retiring employees based on Job Titles to plan hiring for relevant Departments accordingly. Also, determine which employees are eligible to engage in the mentorship program. Team's retiring employees were recognized by job title, which helps to examine employees born between January, 1 1952 and December, 31 1955. 

Initially we applied a query for deliverable 1 that fetch the first_name, last_name and emp_no columns from the employees table and also the title, from_date and to_date columns of the titles table in our pewlett-hackard query. We connected these table on the primary key, applied filter to data by birth_date and give output value into a new table.
For further analysis, we created a unique_titles table to find the first occurance of the emp_no in our new table by using the "DISTINCT ON" function. Finally we did ORDER BY COUNT to show us the total number of employee retiring for each title from our unique_titles table that we generated from data provided. 

Furthermore, for deliverable 2 we created a query that retrieved columns from our employees and dept_emp table, filter data on current employees born in 1965 then sort the table by emp_no.

## Results

<li>With the retirement_titles table we are able to determine eligibility for employee to retire and how long they have served at each position with Pewlett-Hackard during their career.</li>

### Script:
![retirement_titles](https://user-images.githubusercontent.com/86158802/129496097-7ac19e48-c734-4a5e-b71d-f3767269a43f.PNG)

### Output:
![retirement_titles_output](https://user-images.githubusercontent.com/86158802/129496099-5933c70f-1704-4734-aa86-7b19b090ee70.PNG)

<li>The unique_titles table that we generated is helps to find the most recent job title for employees of retirment age.</li>

### Script:
![unique_titles](https://user-images.githubusercontent.com/86158802/129496107-5d72319e-041c-481d-bccd-112e516371af.PNG)

### Output:
![unique_titles_output](https://user-images.githubusercontent.com/86158802/129496109-9d0ca060-3af9-4ef5-86b0-040b7c7510c4.PNG)

<li>Our retiring_titles point out the majority of the employees of retirment age (57,668/90,398 = 64%) have senior position titles with firm.</li>

### Script:
![retiring_titles](https://user-images.githubusercontent.com/86158802/129496116-ca08da39-1785-40a5-b063-3cd6c22a0062.PNG)

### Output:
![retiring_titles_output](https://user-images.githubusercontent.com/86158802/129496118-cc808dae-d4ab-4366-8a92-4310542784bb.PNG)

<li>The last part of our analysis show individuals eligible for mentorship, as well head of new csv show us majority of retirement employees having senior job positions</li>

### Script:
![deliverable2-mentorship_eligibilty](https://user-images.githubusercontent.com/86158802/129496129-d84c668c-cf5b-49eb-9a14-0a66cf66507e.PNG)

### Output:
![deliverable2-mentorship_eligibilty_output](https://user-images.githubusercontent.com/86158802/129496133-568644ec-f472-4e4a-9c97-382158c1e042.PNG)

## Summary
<b>1) How many roles will need to be filled as the "silver tsunami" begins to make an impact?</b>

  Our analysis says we need urgent hiring for 90,398 positions as this workforce might retire at any given time
        
![count_retiring_script](https://user-images.githubusercontent.com/86158802/129496017-e0da55ba-8c1c-47d2-88fc-a4ece23d2f76.PNG)
![count_retiring](https://user-images.githubusercontent.com/86158802/129496021-0cfbbe65-e6d7-4869-9a79-d4bd135979ee.PNG)

<b>2) Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?</b>

  According to analysis perfomed we don't have enough employees eligible to participate in mentorship program and number of eligible individual is 1549 only.
        
![count_mentorship_script](https://user-images.githubusercontent.com/86158802/129496027-da7ba164-1382-4498-97e6-9dc307e38e18.PNG)
![count_mentorship](https://user-images.githubusercontent.com/86158802/129496031-47caa818-d142-41ca-bb03-3bfc455c3ecc.PNG)

## Conclusion

By understanding the outcome of analysis, we can see 63% of the workforce is either retiring or their will be many positions to fill over for mentorship program over coming 5-10 years. Also find out this is not enough workforce to sucessfully perform task or current employees doesn't have enough experience to fulfill the senior or mentorship program. 

For further to overcome this issue, Pewlett Hackard need to come up with strategies to get new experienced employees and make it better workplace for current employees by providing better retirement plans and try to match up with current market payrange for Jobs. Also to help their existing employees to enhance their skills by providing education training and working skill training programs. Next hire might need to be done as per need and this might help to keep up work and revenues up. 
