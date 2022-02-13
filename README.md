# Introduction_to_Data_Science_in_Python
Essa foi a minha solução no último projeto para obtenção do certificado no curso Introduction to Data Science in Python, da Universidade de Michigan disponível na plataforma Coursera.

A atividade era a seguinte:

Assignment 4
Description
In this assignment you must read in a file of metropolitan regions and associated sports teams from assets/wikipedia_data.html and answer some questions about each metropolitan region. Each of these regions may have one or more teams from the "Big 4": NFL (football, in assets/nfl.csv), MLB (baseball, in assets/mlb.csv), NBA (basketball, in assets/nba.csv or NHL (hockey, in assets/nhl.csv). Please keep in mind that all questions are from the perspective of the metropolitan region, and that this file is the "source of authority" for the location of a given sports team. Thus teams which are commonly known by a different area (e.g. "Oakland Raiders") need to be mapped into the metropolitan region given (e.g. San Francisco Bay Area). This will require some human data understanding outside of the data you've been given (e.g. you will have to hand-code some names, and might need to google to find out where teams are)!

For each sport I would like you to answer the question: what is the win/loss ratio's correlation with the population of the city it is in? Win/Loss ratio refers to the number of wins over the number of wins plus the number of losses. Remember that to calculate the correlation with pearsonr, so you are going to send in two ordered lists of values, the populations from the wikipedia_data.html file and the win/loss ratio for a given sport in the same order. Average the win/loss ratios for those cities which have multiple teams of a single sport. Each sport is worth an equal amount in this assignment (20%*4=80%) of the grade for this assignment. You should only use data from year 2018 for your analysis -- this is important!

Notes
Do not include data about the MLS or CFL in any of the work you are doing, we're only interested in the Big 4 in this assignment.
I highly suggest that you first tackle the four correlation questions in order, as they are all similar and worth the majority of grades for this assignment. This is by design!
It's fair game to talk with peers about high level strategy as well as the relationship between metropolitan areas and sports teams. However, do not post code solving aspects of the assignment (including such as dictionaries mapping areas to teams, or regexes which will clean up names).
There may be more teams than the assert statements test, remember to collapse multiple teams in one city into a single value!

Question 1
For this question, calculate the win/loss ratio's correlation with the population of the city it is in for the NHL using 2018 data.

Question 2
For this question, calculate the win/loss ratio's correlation with the population of the city it is in for the NBA using 2018 data.

Question 3
For this question, calculate the win/loss ratio's correlation with the population of the city it is in for the MLB using 2018 data.

Question 4
For this question, calculate the win/loss ratio's correlation with the population of the city it is in for the NFL using 2018 data.

Question 5
In this question I would like you to explore the hypothesis that given that an area has two sports teams in different sports, those teams will perform the same within their respective sports. How I would like to see this explored is with a series of paired t-tests (so use ttest_rel) between all pairs of sports. Are there any sports where we can reject the null hypothesis? Again, average values where a sport has multiple teams in one region. Remember, you will only be including, for each sport, cities which have teams engaged in that sport, drop others as appropriate. This question is worth 20% of the grade for this assignment.
