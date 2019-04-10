# college-basketball

# Results and hints for next season's tournament

I finshed in the 96th percentile of all ESPN brackets. Considering I was using this year as a test run, I feel great about the results. I watched less than 5 games this season. The way I predicted the winners of each game was to use the stat lines I produced to compare teams head to head to predict the winner. The stat lines I produced are located in the Rebounds folder of this repository.

# The Good:
The stats where I composed each team's offensive rebounding vs. their opponents defensive rebounds and vice versa (rebs_taken vs rebs_allowed) was very successful. This allows for teams to get extra possesions for potential points.  Another stat that can get teams extra possesions is the turnover margin stat (avg_turnover vs	avg_turnover_forced) which was also successful in predicting a teams success.  For this season, I decided not to weight the stats for each based on how good their conference was and for the most part, that was also successful. I accepted the stats as true when they were for the big conference team's like Duke and did not trust them as much for a smaller team like North Dakota st. For example, Duke had a tournament's best ratio for Rebounds taken which I composed by comparing their offensive rebounds vs. their opponents defensive rebounds on the season. They also shot 47.7 fg % on the season which is above average. Their weaknesses were 3-pt % where they only shot 30.2% percent on the season and had a below average ft% (68.7%). 39.2 percent of all brackets had Duke winning the National Championship and I correctly predicted them to lose against Michigan st. by purely looking at the stats.

# The Bad:

A few things that I would have to incorporate next year more would be to really pay attention to each team's overall fg%. One team that I thought could win a few games in the tournament was Cincinatti. They were a team that out-rebounded and had one of the better TO ratio's in the tournament. But, they lost their first game because they had allowed teams to shoot 35.6% from 3's on the season and shot only 43.2% on all fg's this season. Another thing that would be hard to account for, but something that I really needed, was to matchup up players based on height and weight for starters. Rebounding is not all about height and weight, but if a player has a substantial advantage in those two things, they should have an advantage at getting rebounds, forcing tough shots, and getting blocks. Two of the bad upsets that I predicted were Northeastern over Kansas and Montana over Michigan. Both of those games were never even close even though looking at the stats, I thought they would be. 

# And the Room for Improvement:

If I had more time to do analysis, what I would change next year would be to build a database, possibly through SQL. If i were to Web Scrape all of the data during the season from game threads to find out how much time each player is on the court and the effect they had on statistics while they were on the court, I think I could produce better results. With this information for each team, I can find out what effect they had on the teams overall success. Once I had all of these stats, I will be able to compare players head to head on their statistics to see which players have advantages in their matchups. The reason why I could not use this method was that my current method took about 30 minutes to run. Given that this method would take into account every game on the season (~30 games per team), this method would have taken about 30 times longer to run and I did not have the time to run it this year. With all I learned this, I feel confident that I will have a great prediction system for next year's tournament.
