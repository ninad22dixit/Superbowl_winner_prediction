# **Superbowl LVI winner prediction**
Springboard capstone 3

**Problem Statement:** How can we accurately predict the winner of NFL Super Bowl 2022?

**Context:** ‘Super Bowl’ is the annual championship game of the National Football League (NFL). It is played between the winners of National Football Conference (NFC) and American Football Conference (AFC) leagues. It is estimated that 23.2 million people wagered nearly 4.3 billion USD on ‘Super Bowl 2020’ played between the Tampa Bay Buccaneers and Kansas City Chiefs. Thus, predicting the NFL champion accurately can be financially quite beneficial. Developing a robust model to predict the winner can also highlight the most important factors that make a particular football team successful. It may help teams in devising better game plans and improving recruitment strategy.

**Source:** https://www.thelines.com/super-bowl-how-much-money-bet/

**Criteria for success:** Given the teams’ records in regular season and playoff games, predict the winner between the Los Angeles Rams and Cincinnati Bengals.

**Scope of solution space:** Data collected over only the 2021 season will be used for this analysis.

**Data source:** https://www.pro-football-reference.com/ 

**Constraints:** This analysis does not take into account the absence of notable players due to injuries. Performance of special teams is either included in the offensive performance (e.g., field goal kicker), defensive performance (turnover of ball possession), or not included at all (punter statistics).

**Project strategy:** 
1. Estimate performance statistics of the two teams playing Super Bowl LVI.
2. Develop a regression model that accurately determines the scores from previous games played in the season.
3. Input the estimated feature values in the model to predict the score for each team.

 The team that’s estimated to score more points is the projected winner.
