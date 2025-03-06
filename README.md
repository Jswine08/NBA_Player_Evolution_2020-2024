## NBA_Player_Evolution_2020-2024
Link to Capstone: https://app.powerbi.com/view?r=eyJrIjoiZjYzZDVjODktYjA5Ni00ZjhlLTg0MWQtNmM1YWUwYjE5YTk2IiwidCI6IjEwMWRhNTg3LTE4NDMtNGY1Mi04YjhhLTE3YjA2OWM2NmQzMyIsImMiOjJ9
## Table of Contents
* [Motivation](#motivation)
* [Questions](#questions)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Sources](#sources)
* [Conclusion](#conclusion)

# Motivation
Ever since I was a kid, watching sports has been a passion of mine. The team driven atmosphere mixed with competitiveness is what drew me to it. Basketball was one of the first sports I played because of my height. As I got older, my friends and I would debate whose teams were better, or even who was the greatest at their position of all time (Jordan vs Lebron). This is what got me to compare statistics to each others careers/teams and try to find the reason behind their wins. That’s what led me to this project in hopes of getting a deeper analytical understanding of this.

## Questions:
1) How do the top and bottom 10 NBA teams compare statistically using assists, turnovers, rebounds, free throw attempts, and steals over the years between 2010-2024?
2) Are there any statistical factors that strongly correlate with total wins in the NBA from 2010-2024?


## Problems and Hurdles
Here were a few obstacles I found as I was working through this project:
•	Team color code per graph: I originally wanted the team colors that I had on the first top 10 slide to change for each graph when I selected the name in the slicer, but since the graphs were yearly averages, it didn’t quite work as planned. Instead, I had to pick a different team color from that first slide for each slide to help keep things consistent.
•	Missing Team Data: When I was calculating the bottom 10 winning teams, there was missing data from a few years of a few teams. I figured out that some teams changed names over the years, causing gaps in my dataset. I had to change the original name to the one with the most data in the csv. After that, there were no issues.
•	If I were to dive into this further I would look into individual players and their impacts on the teams wins.


## Technologies Used
1) Python / Pandas - for exploration, normalizing and aggregation of the dataset
2) Power BI - for creating interactive   dashboard and presentation
4) Git- for data storage
5) Excel - Data exploring
6) Table Heatmap – Correlation analysis



## Data Sources
1) Data Source: [https://github.comhttps://github.com/NocturneBear/NBA-Data-2010-2024/NocturneBear/NBA-Data-2010-2024](https://github.comhttps://github.com/NocturneBear/NBA-Data-2010-2024/NocturneBear/NBA-Data-2010-2024)
2) Theme JSON Source: [BIBB | Power BI Theme Generator](https://powerbithemegenerator.bibb.pro/)
3) Pictures: [The NBA’s Best Assist Combos of the 2000s - The Ringer](https://www.theringer.com/2020/03/09/nba/best-assist-combos-nash-amare-stockton-malone-lebron-davis), [NBA champions through the years](https://www.usatoday.com/picture-gallery/sports/nba/2018/05/03/nba-champions-through-the-years/34535415/), [Top Ten All-Time NBA Playoffs Turnover Leaders: You Might Be Surprised!](https://bleacherreport.com/articles/712370-top-ten-all-time-nba-playoffs-turnover-leaders-you-might-be-surprised), [The Energy of Innovation lives in every Acura SUV](https://www.youtube.com/watch?v=0a1IesEOkps).  
4) Definitions: [Wikipedia](https://www.wikipedia.org/)
5) Correlation Explanation: [How to Calculate a Correlation Coefficient in Power BI](https://www.statology.org/power-bi-correlation-coefficient/)


## Conclusion
1) Assists and Rebounds have the strongest positive correlation with wins. If I were a coach I would focus on these 2 the most.

2) Turnovers have a slightly negative correlation. So giving up the ball to the opponent isnt as bad as you would think.

3) Steals and free throw attempts have low positive correlations. While defense is important, steals alone don’t directly translate to more victories. Likewise, getting to the free-throw line more often doesn’t appear to be a game-changer.

4) Looking back on the second data question, we can see that there isnt one statistic that strongly correlates with wins.

5) Ultimately, winning teams prioritize a combination of ball movement, efficient scoring, securing possession after missed shots, and minimizing turnovers. This analysis provides a data-driven perspective on what separates top teams from the rest. A coach cannot solely focus on one statistic for winning, but a few with a positive correlation should help improve their chances at winning.
