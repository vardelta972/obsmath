For limsup we just let the starting index of sup tend to infinity and see what happens, similarly for liminf we let the starting index of inf tend to infinity and see what happens.

Remember these: sup decreases as index increases and inf increases as index increases.
# Properties
![[Pasted image 20231228165050.jpg]]
![[Pasted image 20231228165100.jpg]]
![[Pasted image 20231228165113.jpg]]
![[Pasted image 20231228165121.jpg]]


# For Functions
Questions are from Kaczor
$$
\lim  \sup_{x \to c} f(x) := \lim_{ \varepsilon \to 0^+ } \sup _{x \in B_{\varepsilon}(c)/\{ c \}} f(x)
$$
Here observe the argument function of epsilon increases.

Similarly
$$
\lim  \inf_{x \to c} f(x) := \lim_{ \varepsilon \to 0^+ } \inf _{x \in B_{\varepsilon}(c)/\{ c \}} f(x)
$$
Here the argument function of epsilon decreases 

It turns out that:
$$
\lim  \sup_{x \to c} f(x) := \inf _{\varepsilon >0} \sup _{x \in B_{\varepsilon}(c)/\{ c \}} f(x)
$$
Similarly
$$
\lim  \inf_{x \to c} f(x) := \sup _{\varepsilon >0} \inf _{x \in B_{\varepsilon}(c)/\{ c \}} f(x)
$$
The proof as given as follows: (using [[Limits#Sequential Criterion ]] and [[MCT]])

## Relationship With The [[Oscillation Number]]

### Relation With Limits