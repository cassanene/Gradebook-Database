# Problem Statement
We are asked to implement a grade book to keep track student grades for several couses that a professor teaches. Courses should have the information of department, course number, course name, semester, and year.  For each course, the grade is caculated on various categories, including course participations, homework, tests, projects, etc.  The total percentages of the categories should add to 100% and the total perfect grade should be 100. The number of assignments from each category is unspecified, and can change at any time.

# How to install mysql in your terminal

Head to MySQL's website and download the community server. After downloading, head to your terminal and open your .bash_profile file. Insert this line into that file:

```vim
export PATH=${PATH}:/usr/local/mysql/bin/
```
Then save the file, terminate your termianl, boot it again. 

Enter this line to get your mysql server running:

```bash
mysql -u root -p
```

# How to Run

If you know how to use MySQL, start it up on your local computer's terminal. Then enter the line

```sql
CREATE DATABASE GRADEBOOK;
```

then after that line use the database by doing:

```sql
USE GRADEBOOK;
```
After inserting this line you should be able to use every line in the .sql file and the database will be created.

If you are not able to use MySQL in your terminal, you can head to this link(https://replit.com/@CasseyAnene/Gradebook-SQL) with the source code and view the outputs.

