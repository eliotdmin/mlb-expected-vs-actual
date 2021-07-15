# mlb-expected-vs-actual

Batting average (BA) is widely recognized as one of the most important MLB
statistics, with the league leaders in batting average awarded annually and
recognized for their excellent hitting. With the development of statcast (an
advanced metric tracking software) in the last decade, however, predictive
statistics such as xBA (expected batting average) have come to the forefront.
Expected batting average ignores the outcome of each batted ball, but calculates
the probability of a hit based on the batted ball's velocity, angle, and, in the
case of a ground ball, the player's speed.

Often, xBA falls slightly above or below a player's actual batting average (At
the time of writing, on July 12, 2021, the average absolute difference between
xBA and BA across the 2020 and 2021 seasons is .0185). The metric derives its
usefulness from the ability to juxtapose a player's batting average with his
expected batting average: a player whose batting average falls below his
expected batting average is expected to experience positive regression, while a
player whose batting average falls above his expected batting average is
expected to experience negative regression. As an extreme example, a player who
has a batting average of .330 — an excellent batting average — but an expected
batting average of .270 should not expect to his .330 for the rest of the
season. Conversely, an individual hitting .220 with a .260 xBA should see his
fortunes reverse soon.

In this analysis, I use statcast data collected from 2017 onwards to show that
xBA would more accurately serve as a predictor of batting average if it were to
take pull tendency — the tendency of a right-handed batter to hit the ball to
left field — into consideration. Specifically, hitters who utilize all fields
and aren't too pull-heavy are more likely to overperform their xBAs, while
hitters who are pull-heavy are likely to underperform their xBAs. This has
interesting implications for the xBA statistic, including but not limited to the
possible adjustment of xBA based on pull percentage.

<img width="874" alt="Screen Shot 2021-07-14 at 8 21 54 PM" src="https://user-images.githubusercontent.com/60484287/125709088-4df630d4-6d19-41e3-a5a5-8e062b585c1b.png">
