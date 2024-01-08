### Binary Search 
You half the given stuffs into stuffs and look for the desired stuffs in those stuffs. Basically divide and conquer.
[[Ancient Bisection Method]] is an example.

#### Examples
##### Number Guessing Game
You are given an interval $[a,b]$ i guess an integer there and your job is to find it, at each set i tell you whether your guess is correst, too high, too low. Then is it possible for you to win? #mpro #pro #ipro 

We use binary search to find that number. At first step we guess any integer there then if the answer is yes we done if no we divide this interval into halves around that integer and choose the one according to the feedback given then repeat. This process must terminate by the [[Principle Of Infinite Descent]]. Thus at the last stage our guess must be correct since after dividing no two of the new intervals contain an integer. DO THE NO OF GUESSES REQUIRED LATER.

### Greedy Algorithm 
Prioritises short term benefits to prove propositions.
