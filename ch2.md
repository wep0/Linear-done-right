# Ch 2. Finite-Dimensional Vector Spaces



## 2A. Span and Linear Independence

**Linear Combination**: for $v_1,...,v_m$, its linear combination is $a_1v_1 + ...+a_mv_m; a_i \in F$

*2.4 Example 2*:

$(17,-4,5) = a_1 (2,1,-3)+ a_2 (1,-2,4)$ 

get the system of equations
$$
17 = 2a_1 + a_2\\
-4 = a_1 - 2a_2\\
5 = -3a_1 + 4a_2
$$


**Span:** $span(v_1,...,v_m) = \{a_1v_1 + ...+a_mv_m: a_1,...,a_m \in F\}$

*The span of the empty list is defined to be $\{0\}$*

**Span is the smallest containing subspace:** The span of a list of vectors in $V$ is the smallest subspace of $V$ containing all the vectors in the list.

*More clear proof:* 

Suppose $v_1, ...,v_m \in V$

First we want to prove $span(v_1, ...,v_m)$ is subspace in $V$

*additive identity*: $ 0 = 0v_1 + ...+0v_m$

*closed under addition*: $(a_1v_1 + ...+a_mv_m) + (b_1v_1 + ...+b_mv_m) = ((a_1+b_1)v_1 + ...+(a_m+b_m)v_m)$

*closed under addition*: same



**Noted**: The ***smallest*** subspace $M$ of $V$ containing $v_1,...,v_n$ means every subspaces of $V$ containing $v_1,...,v_n$ contains $M$



**Spans(verb)**: If $span(v_1,...,v_m) = V \implies v_1,...,v_m$ spans $V$.

**Finite-dimensional vector space**: A vector space is called ***finite-dimensional*** if some list of vectors in it spans the space.

**Polynomial $\mathcal{P}(F) $**: 

$p: F \to F$ is called a *polynomial* with coefficients in $F$ if $\exist a_0,...,a_m \in F$ such that
$$
p(z) = a_0 + a_1z + a_2z^2 + ...+a_mz^m
$$
for all $z \in F$

$\mathcal{P}(F)$ is the set of all polynomials with coefficients in $F$

