States that every number bigger than 1 can be written as a product of primes
$$
n = \prod p_{j}^{q_{j}}
$$
where pj forms a strictly increasing sequence, in a unique way.

### Proof By Infinite Descent 

#pro #mpro #ipro -> We first prove that every n>1 has atleast one prime divisor. Say there is an n>1 with no prime divisors. Then n is composite implying $\exists 0< n_{1}<n$ which divides n. Now n1 itself cannot be prime, so we repeat this procedure again and again to get a seq in infinite descent. 
Now we prove that every n>1 is a product of primes. We do the following algorithm we choose a prime p dividing n then write n=kp then we do this to k and so on... Observe we get a sequence(starting with k) strictly decreasing which must terminate implying we have written n as a product of primes.

##### Proof Of Uniquenesses 
