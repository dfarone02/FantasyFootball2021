# FantasyFootball2021
Some statisitics and lasso regression model for a 2021 Fantasy Football League of 10 teams
to see what statistics and traits were most prevalent among the 4 teams that made the playoffs and the team that won the playoffs:

The stats that are measured to see what is most important to a team's success are:
      Wins- How many weeks a team won their matchup over 14 weeks.
      
      Losses- How many weeks a team lost their matchup over 14 weeks.
      
      WinPct- Wins / 14 weeks
      
      PtsFor- Total Points Scored in the season
      
      PtsAgnst - Total Points scored on that individual team during the season
      
      AveOppWinPct- The average of the Win Percentage of the opponent of an individual team over a course of 14 weeks
      
      QBPts- Total points for the Quarterback Position
      
      WRPts- Same as above, but for the Wide Receiver position
     
      TEPts- Same as above, but for the Tight End position
     
      Flex same as above, but for the Flex(Pick a WR or TE or RB that week) position
      
      DSTPts- Same as above, but for the Defense/Special Teams position
      
      KPts- Same as above, but for the Kicker position
      
      Moves - How many times a team added, traded, or released one of their players
      
      DraftPick- What pick out of 10 did the individual team has (Draft order: 1,2,...,10)

At the 90% confidence level and alpha = 0.1 significance level: -QBPts, TEPts, and KPts have a slighlty negative impact on the lasso regression. -RBPts, WRPts, FlexPTS, DST Points had a slightly positive impact on the lasso regression.

Basically, the people who did not make the playoffs had the better quarterbacks, tight ends, and kickers and those who made the playoffs had better runningbacks, wide receivers, flex(qbs or wrs), and defense/special teams

Practically nothing can be taken from this model since it only had a sample size of 10 teams, but if anything can, it is that those who want the best chance of winning should focus on quarterbacks, wide receivers, flex, and defense/special teams in this league's draft

The most interesting aspect to take away is to see which teams had the best at a position and to see if a team that had the best player at a specific position made the playoffs.
