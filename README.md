# Pewlett Hackard Analysis

## Overview of Project
In this project, I was asked to help Bobby prepare for the upcoming wave of retirement at Pewlett Hackard, which they are calling the "silver tsunami". To complete this analysis, I was given the following tasks:
- Create a database of the employees that are reaching retirement age
- Determine the number of retiring employees per title
- Identify employees who are eligible to participate in a mentorship program

## Results
After completing this analysis, I gathered the following results:
- 90,398 employees at Pewlett Hackard are reaching retirement age.
- The majority of retiring employees are either Senior Engineers or Senior Staff.
  - The full breakdown of retiring employees by title is shown below
  - ![Retiring Employees by Title](data/titles.png)
- Only 1,549 employees are eligible to participate in the mentorship program.
- After the "silver tsunami", the number of employees at Pewlett Hackard will drop from ~300,000 to ~210,000.

## Summary
As mentioned above, as the "silver tsunami" begins to make an impact, Pewlett Hackard will have to fill approximately 90,000 roles. With only 1,546 employees eligible for the mentorship program, there are not nearly enough employees to mentor the next generation of Pewlett Hackard employees. However, if the company decides to hire in smaller waves, perhaps each mentor can be assigned to a group of new hires. To see the breakdown in mentorship eligible employees by department, I've run the query below and achieved the following results.

  ![Mentor Query](mentor_query.png)
  
  ![Mentor by Department](mentor_dept.png)
  
Looking at the results above, mentors and new employees can be broken down by department for training. There are the highest number of mentors in the Development, Production, and Sales departments. To see if this matches up with the hires that will be necessary following the "silver tsunami", I've run a similar query to determine the breakdown of retiring employees by department.

  ![Retiring Query](retiring_query.png)
  
  ![Retiring by Department](retiring_dept.png)
  
Looking at the results, the majority of retiring employees come from the Development, Production, and Sales departments. This matches up with the proportions of employees eligibile for the mentorship program. This is helpful information to have, because we now know the number of mentors will line up with the necessary new hires when divided by department. 
