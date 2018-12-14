---
title: Are NFL Players Overvalued?
subtitle: Finding out who is earning their paycheck
image: /img/football.jpg
---

As a long time suffering fan of the NFL Minnesota Vikings, I am aware of how fickle football fans can be. Given their high salaries fans can become angry at players who they feel are under-performing. NFL players get paid to play the game at a very high level. However, sometimes one might feel that players who do not affect the final outcome of games are being overpaid. 

I decided to put my data skills to work and find data to prove that some players are, in fact, not doing enough to make their fans happy. I found data on player salaries and scoring on the [Pro Football Reference](https://www.pro-football-reference.com) website. Upon downloading this data and cleaning it up a bit, I was able to find out which players are the highest scoring and their salaries.  

![Image](/img/codesnip.PNG)

I have the data showing each player's name, position, salary, team and points scored. This allowed me to chart the salary versus the points scored during games. The purpose is to show the value that these players bring to their team and support the view that certain players deserve the fan consternation they receive. 

![Image](/img/initialchart.png)

My initial chart shows that almost all the players who have scored points in a game during the 2017 season fall into the lower left corner of the chart. This makes it difficult to see which players are in this group with so many data points. 

To address this problem, I filtered out the players who scored less than 40 points during the season. This drops the players who are not expected to score points, such as linemen and linebackers. When these players do score, it is not only unexpected, but also not something the team can count on each week. 

This reduced the number of players in the lower left corner of the graph, but not by a large amount. I then also removed players whose salary was less than $1,000,000 per season. This should gave me a better idea of which players are really paid to actually score points every week and help their team win. Each team's final win-loss record will rely on these players. 

<iframe height='840' width='450' scrolling='no' title='XoXaRL' src='//codepen.io/brianbehnke/embed/XoXaRL/?height=809&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/brianbehnke/pen/XoXaRL/'>XoXaRL</a>NFL Player Value</a> by Brian (<a href='https://codepen.io/brianbehnke'>@brianbehnke</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

In this interactive chart, I also added the player's position as symbols. This helps to determine each player's value relative to others who play the same position. Using the drop down menu, you can select the specific position. Those positions will then be highlighted. 

![Image](/img/RB.png)

When selecting Running Backs (RB), most shown fall into a pretty tight grouping, with a couple of outliers. However, it appears that RBs are mid-range with scoring, but they also are on the lower end of the salaries. It seems most RBs are of decent value for their salary and points scored so we can determine that they are earning their salary. They don't factor into wins and losses much, but also do not break the bank on cost.

![Image](/img/WR.png)

Looking at the Wide Receiver (WR) group, we see a much larger range along the salary scale. Most WRs do not score a lot but they appear to get paid very well compared to other positions. I would say that this group is for the most part under performing for their costs to the team. These guys are deserving of the criticism they receive from fans. 

![Image](/img/QB.png)

When we look at the Quarter Backs (QB), we see a much larger spread but the majority are on the higher end for both scoring and salary. Having a much higher average scoring is an indicator that the QB position plays a large role in scoring and a team's record. However, several highly paid players have similar scoring to much lower paid players, which makes me believe that the QBs receiving a higher salary than the majority are over paid. Teams do appear to be able to pay players in this position much less and still expect similar scoring results. 

As a fan of the NFL, I understand this type of analysis is far from complete, but it is fun to be able to feel vindicated when my anger is supported by these charts. The players on my favorite team need to play better and win more games. The low average cost of RBs was surprising. They make much less than the other skill positions, as well as some defensive players who do not add much in terms of scoring. 

![Image](/img/salary.png)

![Image](/img/scoring.png)

I will continue to root for the Minnesota Vikings and still get angry at them when they do not win. With this analysis I can deduce that not all players are over paid. I still appreciate the effort that goes into playing football at this level. <span style="color:purple">Skol Vikings!</span>Skol Vikings!

