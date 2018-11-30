---
title: Project Starting Point
subtitle: 
image: img/nflmap.jpg
--- 
My portfolio project will be an analysis on NFL salaries and in-game scoring for the 2017 season. I will analyze who is earning their salary based on how much the player aids in the final score of the games.

I am interested in trying to find a way to determine a NFL player's relative contractual worth. I feel that a higher paid player should more directly affect a game and the team's ability to achieve victory. Showing the value of the contract pitted against the players contractual value is a good sign of a player's worth to the team.

Many fans enjoy celebrating the success of their team but also enjoy complaining about a player who does not do enough to help their team. Considering the amount of money they may be getting paid. Sports forums are a fun place to watch the fan's consternation with players who they feel are under performing. Fans can be brutally open about their opinions. And yet many fans likely do not know the player's true worth to the team. Especially in aspects that may not relate to the final score of the game.

My analysis will be one way to show a player's value based on their ability to help determine the score of the game. I understand that there are plenty of positions that will not factor into the scoring. But many do bring a measure of influence to the score but do not actually get credit for points scored. I will leave that discussion and analysis for the next project. There I will determine player value without looking only at scoring.

# My data sources:

[Pro Football Reference](https://www.pro-football-reference.com/years/2017/scoring.htm)

[Pro Football Reference](https://www.pro-football-reference.com/players/salary.htm)

![Image](https://i.imgur.com/8OltDf0.png)

This is the main source of the data I am going to be working with. It provides all the scoring and salary information that I need for each player in the NFL for the 2017 season.

This is a full fledged statistical treasure trove for many sports. The site conpiles data for Baseball, Football(professional and college), Basketball(professional and college), hockey, and soccer.They have several years worth of data available for all of these sports and allows for easy down of the data in csv format. If you are doing a sports analytical project this IS the place to find it. 

In the NFl pages there is information on players and teams and their statistics, statistical rankings,  awards, salaries, draft information and well as about coaches, executives and officials. There is not much data you would want that you can't find at this site. 

I am focused on looking at individual player's statistical performance and salary. This information is easily found on the website and it is provided in csv format for easy download. The site is easy to navigate with many pre-filled pages showing rankings on players and salaries. 

I will be back to this page for future use, even if just for informational purposes and not for a project, as there is so much information it is a joy to look through. 
***

[Spotrac contract](https://www.spotrac.com/nfl/contracts/)

![Image](https://i.imgur.com/DIBORG0.png)

This site shows salary related information for all players and teams. It provides a nice way to see the full contract figures for all players, rather than a 1 year shapshot. 

This site is great for finding a lot of player salary information. While it does not provide scoring data we can find player's contract details, including bonuses and incentives as well as fines. 

This site also provides a year by year breakdown of contracts and how much money is guaranteed and how much is not. It gives a information on when players will be eligible to renegotiate their contract and lengths of contracts. There is a lot to digest here, but much of this is beyond the scope of my current project. This will be worth coming back to for followup projects though. 
***

[HIghest paid NFL players per position](https://howmuch.net/articles/highest-paid-NFL-player-at-every-position)

![Image](https://i.imgur.com/yGyyC2j.jpg)

This site breaks down the highest paid players by position. We can then see which positions make the most money even if they do not score points during the games. 

While this site does not provide a full list of salaries for all players, it only gives a snapshot of the highest paid player at each position. This can be useful to see which positions we would expect to have the highest salaries. 

Also, knowing some information about the types of positions that are more likely to be involved in scoring points we see a higher values placed on those positions, Quarterback, Running Back, Wide Reveiver and Tight Ends. It will be interesting to see which positions are undervalued and overvalued based strictly on scoring as this chart shows that many non-scoring positions still have high salaries. 


Since the data I am looking at is related to a sports theme, I found that there is an abundance of it out there. Not only is the information easy to find, it is also readily available in handy downloadable csv format. 

Steps I have already completed: 
- Identify the project goals
- Find relevant data online
- Download data locally
- Initial inspection of data headers and values
- Quick charting examples using Tableau Prep and Tableau Desktop

Next steps in my analysis process:
- Create a stronger hypothesis
- Import data into Python local environment
- Data wrangling to get the data in the simplest format for the values I want to analyze
- Simple charting to ensure the data I have works for my hypothesis
- Expand on the analysis to include position and team versus salary and scoring as well
