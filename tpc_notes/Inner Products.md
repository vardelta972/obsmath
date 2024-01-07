## On Real vector Spaces
Its a function $<> : V*V \to R$ so that
$$ \begin{matrix}
<u,v> = <v,u> \\
<u+v,w> = <u,w> + <v,w> \\
<\lambda u,w> = \lambda <u,w> \\
<v,v> \geq 0, <v,v > = 0 \iff v=0
\end{matrix}
$$
One inner product spaces a norm can be automatically defined
$\mid v| = \sqrt{ <v,v> }$, thus it atuomatically has a metric space structure. That distributativty law allows it to be treated like a polynomial.

## Example: Consider all function mapping $[0,1]$ to R that are smooth then define inner product as 
$$
<f,g> = \int_{0}^1 fg \, dx 
$$
Cauchy Swarchz inequality holds in inner product spaces see [[On Cauchy and Holder's Inequality]].

## Generalised Notion Of Angle

$$
\theta = \cos^{-1}\frac{<u,v>}{|u||v|}
$$
for two non-zero vectors, Note this definition is possible thanks to cauchy swarchz.
