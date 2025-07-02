# Data
-   **NCAA Men's March Madness**: This data set is taken from Nishaan Amin's Kaggle dataset analysis which
predicts March Madness outcomes. March madness is the NCAA Division I basketball tournament. It is a single
elimination style tournament with 68 teams that compete in 6 rounds for the national championship. The two
data sets below contain information regarding yearly past team results and the yearly public picks data.

# Codebook for NCAA Men's March Madness Dataset

## Variable Names and Descriptions:

Team Results Data

- TEAMID: Unique identifier for the team.
- TEAM: Division I college basketball team name.
- PAKE: Performance against Komputer Expectations.
- PAKERANK: Rank of PAKE from all teams.
- PASE: Performance Against Seed Expectations.
- PASERANK: Rank of PASE from all teams.
- GAMES: The total amount of tournament games the team has played.
- W: The total amount of tournament game wins.
- L: The total amount of tournament game losses.
- WINPERCENT: The winning percent of the team.
- R64: Amount of times the team made it to the Round of 64.
- R32: Amount of times the team made it to the Round of 32.
- S16: Amount of times the team made it to the Sweet 16.
- E8: Amount of times the team made it to the Elite 8.
- F4: Amount of times the team made it to the Final 4.
- F2: Amount of times the team made it to the Finals.
- CHAMP: Amount of times the team was a Champion.
- TOP2: Amount of times the team was awarded a 1 or 2 seed.
- F4PERCENT: Likelihood of a team getting to at least 1 Final Four.
- CHAMPPERCENT: Likelihood of a team winning at least 1 Championship (per efficiency rating).
    
    
Public Picks Data

- YEARL: Ending year of the team's season
- TEAMNO:	Unique identifier for the team and the year they played in
- TEAM: Division I college basketball team name.
- R64:	The percent of people who picked the team to win the game in the Round of 64.
- R32:	The percent of people who picked the team to win the game in the Round of 32.
- S16: The percent of people who picked the team to win the game in the Sweet 16.
- E8:	The percent of people who picked the team to win the game in the Elite 8.
- F4:	The percent of people who picked the team to win the game in the Final 4.
- FINALS:	The percent of people who picked the team to win the game in the Finals.

Matchup Data

- year: Tournament year
- round_of: Teams left per round
- winning_team_name: Name of winning team
- winning_team_seed: Seed number of winning team
- losing_team_name: Name of losing team
- losing_team_seed: Seed number of losing team
- losing_team_score: Losing team's score
- winning_team_score: Winning team's score




## Data Types:

Team Results Data

- variable/class	
- TEAMID:	integer	
- TEAM:	character	
- PAKE:	double
- PAKERANK:	integer	
- PASE:	double	
- PASERANK:	integer	
- GAMES:	integer	
- W:	integer	
- L:	integer	
- WINPERCENT:	double	
- R64:	integer	
- R32:	integer
- S16:	integer	
- E8:	integer
- F4:	integer	
- F2:	integer	
- CHAMP:	integer	
- TOP2:	integer	
- F4PERCENT:	character	
- CHAMPPERCENT:	character	


Public Picks Data

- YEAR:	integer
- TEAMNO:	integer
- TEAM:	character
- R64:	character
- R32:	character
- S16:	character
- E8:	character
- F4:	character
- FINALS:	character

Matchup Data

- year: integer
- round_of: integer
- winning_team_name: character
- winning_team_seed: integer
- losing_team_name: character
- losing_team_seed: integer
- losing_team_score: integer
- winning_team_score: integer