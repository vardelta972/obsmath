If a function is [[uniformly continuous]] on a dense set then it can be extended to whole of R whilst still keeping it [[uniformly continuous]].
Source [[##OlympiadQPs/##Romania/RMC 2007.pdf|RMC 2007]]

#pro Extend f as follows given any x in R/D define
$$
f(x) = \lim_{ n \to \infty } f(d_{n}) 
$$
where dn is a sequences in D converging to x, and this limit exists because of [[Uniformly Continuous#IMPORTANT FACT]] and is well defined as it does not depend on the exact choice of dn because of [[Uniformly Continuous#Sequential Criterion]]. Then for each seq an conv to x we can squeeze f(an) using [[density]] of D from here result follows. Infact f is [[uniformly continuous]] over whole of R! #pro 

 ✅ 

# Counterexample In Continuous Case

Consider 1/x on R/0, this is dense in R but ofcourse it cannot be continuously extended to R cuz of singularity at 0, also observe its also not [[uniformly continuous]] on that dense set R/0.