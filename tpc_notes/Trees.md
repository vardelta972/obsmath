A graph is a tree where any two vertices are connected by a unique [[simple path]]. If there is atmost one simple path then its a forest. 

# Number Of Labelled Trees
Actually number of trees with n vertices is not known but this changes when we introduce labels. We can encode a tree with n labelled vertices as a sequence of length $n^{n-2}$ using the following algorithm 

First remove the lowest labelled leaf and append it's neighbour.
Repeat.

Proof that it actually gives a valid encoding:
# Labelled Trees And e

Probability that we get 1 as a vertex when choosing a tree with n labelled vertices =
$$
\frac{(n-1)(n-1)^{n -3}}{n^{n-2}} = \left( 1-\frac{1}{n} \right)^{n-2}.
$$

Thus the probability that we get 1 as a vertex when choosing from trees with infinitely many labelled vertices is DRUM ROLL

$$
\frac{1}{e}
$$
YES e is EVERYWHERE!!