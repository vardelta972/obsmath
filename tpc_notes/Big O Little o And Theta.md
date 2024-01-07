### Big O
we say $f=O(g), \ x \to c$ iff for some real M we have
$$
|f(x)| \leq Mg(x)
$$
for some DELETED neighbourhood around c.

This tells f does not grow faster than g around c or infinity.

### Little o
we say $f=o(g), \ x \to c$ iff 
$$
\lim_{ x \to c } \frac{f(x)}{g(x)} =0
$$
Basically means growth rate of g is significantly lower than that if f close to the point c or infinity.
### Theta 
Basically means the two functions are the same in terms of growth ie
$$
f=O(g) , g=O(f) ; \ x \to c
$$
