cf-aug3
=======

Repo for my guessing game project, afternoon of Monday 8/3

This is a simple game, modeled off the pizza topping game we did in class this morning. I added in a "select from 7 different options" feature by giving numerical choices in the alert, and then capturing those choices in the prompt.

I ran into two problems:

1. An error by including a hard return inside of a string. I finally went to Brook for help, and the inclusion of backslashes before the hard returns fixed that problem.

2. Even though I was taking in integers from the prompt, JS was treating the values as strings. That meant using === in the if condition returned false, whereas using == returned true. I solved this by setting the numerical comparator into a string.