Peano Axioms [[Logic 101#Axiom Systems]] are just a list of propositions designed to describe the naturals.

Graph theory interpretation:

Axiom 2.1. 0 is a natural number.
Axiom 2.2. If n is a natural number, then n++ is also a natural number.

Axiom 2.3. 0 is not the successor of any natural number; i.e., we have n++ not= 0 for every natural number n.
Axiom 2.4.  if n++ = m++, then we must have n = m. -> Makes sure no loops in graph of N

Axiom 2.5 (Principle of mathematical induction). Let P (n) be any property pertaining to a natural number n. Suppose that P (0) is true, and suppose that whenever P (n) is true, P (n++) is also true. Then P (n) is true for every natural number n.

Source: TT [[Analysis 1.pdf]]
2.4. Basically states that succersorship is injective and 2.5. has many famous equivalents like [[Well Ordering Principle]] and [[Principle Of Infinite Descent]]