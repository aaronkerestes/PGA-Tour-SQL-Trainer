# PGA-Tour-SQL-Trainer

Here is a copy of some of the codes I ran for this project.


SELECT 
Player_initial_last AS golfer_name, 
hole_par, 
pos,
strokes,
tournament_name,
course,
date,
 FROM `pgagolf.Golf.pgastats` 
WHERE
pos < '10' 
ORDER BY
hole_par, strokes DESC,
pos DESC
LIMIT 1000

This is what I started out with to pull the data about the lowest scoring tournaments in the year.
From here, I was able to see how the scores fluctuated with the seasons, as well as which ones tended to be a lower-scoring tournament.

More to come!
