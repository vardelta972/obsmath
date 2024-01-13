## Product Metric
We define Metric on $\prod X_{j}$ (this is a finite product ) by 
1)  Infinity Metric:
$$
D(A,B)=\max d_{j}(A^j,B^j)
$$
ie simply calculate distance between individual components then take their maximum.

2) p Product Metric

$$
D(A,B) = |(d(a^j,b^j))_{1 \leq j \leq n}|_{p}
$$
This first gets the componentwise distances arranges them into a real vector then computes their lp norm. Observe that the infinity metric is just the p product as p goes to infinity(this is a rather common exercise found at many places )
### Continuity of Metrics
Metric as a real valued function is continuous itself. #pro #mpro #ipro 
This can be done by repeated applications of triangle inequality.