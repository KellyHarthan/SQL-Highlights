# SQL-Highlights
More advanced code blocks with descriptions of the project, the question being answered and the key functions used.

The Lahman Baseball Project
- Extensive ERD containing 15 unique data tables
- Multi layered questions dealing with specific time frames, metrics, constraints

Though this was a team project, I have only included blocks of code for questions that I worked on individually.

QUESTION 1: Find all players who hit their career highest number of home runs in 2016. Consider only players who have played in the league for at least 10 years, and who hit at least one home run in 2016. Report the players' first and last names and the number of home runs they hit in 2016.

Functions Used:
- Window Functions
- EXTRACT
- RANK
- PARTITION
- Subquery
- CONCAT
- INNER JOIN
- Alias- renaming columns

You will see two answers as I refined the original code looking for a more simple approach

QUESTION 2:Find the name and height of the shortest player in the database. How many games did he play in? What is the name of the team for which he played?

Functions used:
 - CTE
 - CONCAT
 - INNER JOIN
 - LIMIT
 - Alias

QUESTION 3. Using the attendance figures from the homegames table, find the teams and parks which had the top 5 average attendance per game in 2016 (where average attendance is defined as total attendance divided by number of games). Only consider parks where there were at least 10 games played. Report the park name, team name, and average attendance. Repeat for the lowest 5 average attendance.

Functions used:
 - Multiple JOINS
 - Aggregate Functions (SUM, AVG, COUNT)
 - LIMIT
 - Alias

Kids Poetry Program

Individual Project. Used 8 different data tables. Tough the content is light-hearted, the questions were fairly complex ad took some solid time and thought to determine appropriate code. Again these are multi layered questions.

QUESTION 1:Two foods that are favorites of children are pizza and hamburgers. Which of these things do children write about more often? Which do they have the most to say about when they do? Return the **total** number of poems, their **average character count** for poems that mention **pizza** and poems that mention the word **hamburger**. Do this in a single query.

Functions used:
 - Aggregate Functions (AVG, COUNT)
 - ROUND
 - Mode change to numeric
 - UNION
 - Alias
 - ILIKE
 - Case Statements

QUESTION 2: Do longer poems have more emotional intensity compared to shorter poems?  No, they are almost exactly identical. See part B
a. Start by writing a query to return each emotion in the database with its average intensity and character count.
 - Which emotion is associated the longest poems on average?  
 - Which emotion has the shortest?

 Functions used:
  - Multiple JOINS
  - CTE
  - Case Statements
  - Aggregate Functions (AVG, COUNT)
  - ROUND
  - Alias
