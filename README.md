# mlb-expected-vs-actual

Batting average (BA) is widely recognized as one of the most important MLB
statistics, with the league leaders in batting average awarded annually and
recognized for their excellent hitting. With the development of statcast in the
last decade, however, predictive statistics such as xBA (expected batting
average) have come to the forefront. Expected batting average ignores the outcome

Often, xBA falls slightly above or below a player's actual batting average. The
metric derives its usefulness from the ability to juxtapose a player's batting
average with his expected batting average: a player whose batting average falls
below his expected batting average is expected to experience positive
regression, while a player whose batting average falls above his expected
batting average is expected to experience negative regression. 

In this analysis, I show that xBA would more accurately serve as a predictor of
batting average if it were to take pull tendency — the tendency of a
right-handed batter to hit the ball to left field — into consideration.
Specifically, hitters who utilize all fields and aren't too pull-heavy are more
likely to overperform their xBAs, while hitters who are pull-heavy are likely to underperform their xBAs. Insofar