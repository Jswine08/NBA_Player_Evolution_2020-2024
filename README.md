## NBA_Player_Evolution_2020-2024
## Table of Contents
* [Motivation](#motivation)
* [Questions](#questions)
* [Problems and Hurdles](#problems-and-hurdles)
* [Technologies Used](#technologies-used)
* [Sources](#sources)
* [Conclusion](#conclusion)

# Motivation
Ever since I was a kid, I’ve loved watching basketball. The older I got, I became more interested in stats by following team and player performances through any sports platform I can find and debating with friends about which teams and players were truly the best (the always debated Jordan vs Lebron greatness). Those conversations usually caused arguments about how they impacted the game(and if their persormance played a larger role than team performance).

## Questions:
1) How do the top and bottom 10 NBA teams compare statistically using assists, turnovers, rebounds, free throw attempts, and steals over the years between 2010-2024?
2) Are there any statistical factors that strongly correlate with total wins in the NBA from 2010-2024?

## Problems and Hurdles
1) Team color coding per graph: I originally wanted the team colors to change after selecting the teams name in the slicer, but since the graphs were yearly averages and not team names, it didn’t work as planned. Instead, I had chose some of the top and bottom teams colors to color code the statistical portion of the presentation.
2) Missing Team Data: Some teams changed names over the years, causing gaps in my dataset. I had to change the original name to the one with the most data in the csv which fixed the issue.
3) Filtering Issues in Python: I probably over-filtered my dataset in Python, leading to misleading Power BI labels. This taught me that Power BI has a lot of different ways to filter data.


## Technologies Used
1) Python / Pandas - for exploration, normalizing and aggregation of the dataset
2) PowerBI - for creating interactive dashboard and presentation
4) Git - for version control
5) Excel - Data exploring

## Data Sources
1) Data Source: [https://github.comhttps://github.com/NocturneBear/NBA-Data-2010-2024/NocturneBear/NBA-Data-2010-2024](https://github.comhttps://github.com/NocturneBear/NBA-Data-2010-2024/NocturneBear/NBA-Data-2010-2024)
2) Theme JSON Source: [BIBB | Power BI Theme Generator](https://powerbithemegenerator.bibb.pro/)
3) Pictures: [The NBA’s Best Assist Combos of the 2000s - The Ringer](https://www.theringer.com/2020/03/09/nba/best-assist-combos-nash-amare-stockton-malone-lebron-davis), [NBA champions through the years](https://www.usatoday.com/picture-gallery/sports/nba/2018/05/03/nba-champions-through-the-years/34535415/), [Top Ten All-Time NBA Playoffs Turnover Leaders: You Might Be Surprised!](https://bleacherreport.com/articles/712370-top-ten-all-time-nba-playoffs-turnover-leaders-you-might-be-surprised), [The Energy of Innovation lives in every Acura SUV](https://www.youtube.com/watch?v=0a1IesEOkps).  
4) Definitions: [Wikipedia](https://www.wikipedia.org/)
5) Correlation Explanation: [How to Calculate a Correlation Coefficient in Power BI](https://www.statology.org/power-bi-correlation-coefficient/)

## Conclusion
Based on everything we have seen, winning teams make an emphasis on ball movement, efficient scoring, and minimizing turnovers. Assists and rebounds contribute positively, while turnovers have the most detrimental effect.
Interestingly, steals and free throw attempts had little impact on wins, showing me that individual defensive stats don’t always translate to overall team success.
This analysis gives a analytical perspective on what separates top teams from the rest. If I had more time, I’d explore additional correlations such as three-point efficiency, clutch performances, and what statistic(s) during the year plays the most important factor in playoff success.
