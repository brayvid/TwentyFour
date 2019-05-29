# TwentyFour
Solver for a generalized version of the game of 24 - https://en.wikipedia.org/wiki/24_Game 

`````
given = [2, 3, 5, 12]
target = 24
twentyfour(given, target)
> ['d $ (c $ (a $ b))', (5, 2, 3, 12), (3, 1, 3), '+, -, *, /']
`````
The function output shows a representation of the solution expression, followed by the order in which the numbers are used, followed by the order in which operations are used ("+" is 0, "-" is 1, etc). 

In the above example, the solution can be read off as 12 / (3 - (5 / 2)) = 24.

