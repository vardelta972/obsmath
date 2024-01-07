Say we have to smoothly join two functions f(x),g(x) in the interval $(a,b)$



![[Pasted image 20240102184344.jpg]] ![[Pasted image 20240102184354.jpg]]

We use the [[bump function]] and let
$$
h(x) = 1+B\left( \frac{x-a}{b-a} - \frac{x-b}{a-b} \right)
$$
This h(x) stays 1 outside $[a,b]$ then once inside it begins the joining process. We conjecture $h(x)p(x)$ does the job, where p(x) is the piecewise function we want to smoothly join(with value 1 in the undefined region). This also gives us an example where a product of a discontinuous function with a smooth function is smooth!


