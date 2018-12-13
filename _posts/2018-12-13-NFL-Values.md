---
title: Are NFL Players Overpaid?
subtitle: Finding out who is earning their paycheck
image: /img/football.jpg
---

As a long time suffering fan of the Minnesota Vikings of the National Football League, I am aware of how fickle fans can be. Being angry at players they feel are under-performing based on the salary they make. NFL players get paid to play the game at the high level that they do. But there are times when it feels that teams are over paying for players who are not affect the final outcome of games. At least not as much as fans feel that they should be. 

So I decided to put my new trained data skills to work and find the data that can prove that some players are not doing enough to make their fans happy. I found data on player salaries and scoring on the [Pro Football Reference](https://www.pro-football-reference.com) website. This allowed me to download this data and clean it up a bit to find out which players are the highest scoring and what their salaries are.  

![Image](/img/codesnip.PNG)

So I have the data showing players name, position, salary, team and points scored. This would allow me to chart the salary versus the points scored during games. This would show us the value that these players bring to their team and fan base. We will finally be able to point to the proof that certain players deserve the fan consternation they receive. 

![Image](/img/initialchart.png)

My initial chart shows that almost all the players who have scored points in a game during the 2017 season fall into the lower left corner of the chart. This makes it difficult to see which players are in this group with so many data points. 

So I decided to filter out the players who scored less than 40 points during the season. This would drop the players who are not expected to score points, such as linemen and linebackers. When these players score it is not only unexpected but not something the team can count on each week. 

This did reduce the number of players in the lower left corner, but not by a large amount. I then decided to also reduce the chart to cut those whose salary was less than $1,000,000 per season. This should give me a good look into the players who get paid to help the team win by scoring points every week. The team's final record will rely on these players. 

<iframe height='840' width='450' scrolling='no' title='XoXaRL' src='//codepen.io/brianbehnke/embed/XoXaRL/?height=809&theme-id=0&default-tab=result' frameborder='no' allowtransparency='true' allowfullscreen='true' style='width: 100%;'>See the Pen <a href='https://codepen.io/brianbehnke/pen/XoXaRL/'>XoXaRL</a>NFL Player Value</a> by Brian (<a href='https://codepen.io/brianbehnke'>@brianbehnke</a>) on <a href='https://codepen.io'>CodePen</a>.
</iframe>

Looking at this interactive chart, I also added the player's position to the chart as the symbols. This would help us determine the players value relative to others who play the same position. Using the drop down menu, you can select the specific position(such as RB). Those positions will then be highlighted. 

![Image](/img/RB.png)

Most of the Running Backs here fall into a pretty tight grouping, with a couple of outliers. But for the most part it appears that RBs are middle of the pack with scoring but they also are on the low end of salaries. It seems most RBs are of decent value for their salary and points scored. We can let up on these guys a little bit. They don't factor into wins and losses but also do not break the bank on cost.

![Image](/img/WR.png)

When we look at the Wide Receiver(WR) group, we see much larger range along the salary scale. Most WRs do not score a lot but they appear to get paid very well compared to other positions. I would say that this group is for the most part under performing for their costs to the team. These guys are deserving of the hatred they receive from fans. 

![Image](/img/QB.png)

When we look at the QBs(Quarter Backs), we see a large spread of scoring and salary with very few low on both of these. Due to the fact that QBs have a much higher average scoring is an indicator that this position plays a large role in scoring and the teams record. But the fact that several highly paid players have similar scoring to much lower paid players makes me believe that the high salary QBs are over paid. Teams appear to be able to pay this position much less and expect similar scoring results. 

As a fan of the NFL I understand this type of analysis is far from complete but it is fun to be able to feel vindicated when my anger is verified by these charts. The players on my favorite need to play better and win more games. The low average cost of RBs was surprising. They make much less than the other skill positions, as well as some defensive players who do not add much scoring. 

![Image](/img/salary.png)

![Image](/img/scoring.png)

I will continue to root for my home town team and still get angry at them when they do not win. But with this analysis I can see that not all players are over paid. I still appreciate the effort that goes into playing football at this level. Skol Vikings!

