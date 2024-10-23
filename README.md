# Visual_Storytelling_Midterm
UNCC Visual Storytelling and Analytics Midterm Project

# Tableau Public Link
[NHL Midterm](https://public.tableau.com/app/profile/hayden.williford/viz/NHLMidterm/Home?publish=yes)

# Data Source
Moneypuck: NHL Stats
https://moneypuck.com/data.htm

# Introduction
I attempted to figure out why the Carolina Hurricanes struggled to perform in the playoffs by analyzing their regular season statistics. I focused mostly on the issue I noticed of the poor ability to capitalize on goal-scoring opportunities. I know the Hurricanes won lots of game and came second in the conference, but with how we played most of the season it seems like we always fall short when it matters most. The goal was to determine how poor goal scoring in high danger opportunities leads to the team losing games we should have won. This is evaluated at the team level per game and also at the player level across the season.

# Data Extraction/Prepartion
One of the reasons I choose Moneypuck as the source was the data was already organized and clean, which allowed me to ingest good data from the start. The one thing that was required though was for the different views that I wanted, I needed multiple sources. I started with the Team Data which included all 32 teams so I filtered it to only the Carolina Hurricanes. I then created a relationship to connect the players on the Hurricanes to their team data. I do not think the relationship was necessary for the final product I created but it was helpful while I went through multiple designs. I also made a relationship between the team file with a second file that include information related to the other 31 teams in the league. I also attached a file I had to create manually in order to determine which teams made it to the playoffs.
![source relationships](https://github.com/user-attachments/assets/46b7f508-e4ed-4038-a3f4-57b0a56e4c9d)

# Future Work
I definitely think it would be worth to explore other attributes in the moneypuck files to try to create a more encompassing evaluation. I focused on goals as it was something I know the Hurricanes struggled with, but winning games takes a lot more than just scoring goals during opportunities. There are a lot of steps that start from the defense that leads up to a good attack in the offensive zone and exploring the statistics about moving the puck and creating opportunities for teammates would be interesting. 
I think one thing I did not have the ability to add but I think would help the dashboards would be including the lines that each player plays on. It is slightly favored towards the players on the first and second lines as they play more minutes than those on the other lines. More playing time usually equates to more goal scoring opportunities, but it also could hurt the players opportunities as they are more exhausted.
