# Ch.1

**Complex numbers:**  $C: \{a + bi, a,b\in R\}$ 

**Addition & multiplication on $C$**

 **Properties of arithmetic on $C$**:

**Example 2.4**: 

Prove $ab = ba, \forall a,b \in C$

**Notation $F: R \cup C$**

$R^2, R^3: \{(x,y)\}, \{(x,y,z)\}$

**List and Sets**:

 **List**: $(3,5) \neq (5,3), (4) \neq (4,4) \neq (4,4,4)$ 

**Sets**: $\{3,5\} = \{5,3\}, \{4\} = \{4,4\} = \{4,4,4\}$

**Notation** $F^n : \{(x_1,...,x_n), x_j \in F, j = 1,...,n\}$

**Addition in $F_n$**: $(x_1, ...,x_n) + (y_1,...,y_n) = (x_1+y_1,...,x_n + y_n)$

$x,y\in F^n, x+y = y+x$

**Definition of 0**: $0 = (0, ..., 0)$ (length $n$)

**Additive inverse in $F^n$**: $x + (-x) = 0$

**Scalar multiplication in $F^n$**: $\lambda (x_1, ...,x_n) = (\lambda x_1,...,\lambda x_n)$

**Field**: A set containing at least two distinct elements $\{0, 1\}$ 

## 1.B

**Vector space** comes from properties of **addition** and **scalar** **multiplication** in $F^n$

 e.g. $V$ is a **vector space** over $F$;  $R^n$ is a vector space over $R$.

**Set of functions**: $F^S: S \to F$

**Sum of $f, g, \forall f,g\in F^S$ **: $f+g \in F^S: (f+g)(x) = f(x) + g(x)$

**Product**: $\lambda \in F, f \in F^S, \lambda f \in F^S$: $(\lambda f)(x) = \lambda f(x) | \forall x \in S$

**Definition of vector space of $F^S$**: 

1. *Additive identity*: $f_0: S \to F, f_0(x) = 0$
2. *Additive inverse*: $-f(x) = -f(x), \forall x \in S$

**Unique Additive identity** : Suppose $0, 0'$ are both addictive identities for $V$

$0 = 0 + 0' = 0'+0 = 0' \implies 0 = 0'$

**Unique additive inverse**: Suppose $V$ is a vector space and $v \in V$, suppose $w , w'$ are additive inverse of $v$

$\implies w = w + 0 = w + (w + v) = w + (w' + v) = w' + (w + v) = w' + 0 = w'$

**Define $-v, w-v$**: $-v$ is the additive inverse of $v$, $w - v = w + (-v)$ 

**The number 0 times a vector**: 

$0v = (0+0)v = 0v + 0v \implies 0v + (- 0v) = 0v + 0v + (- 0v) \implies 0v = 0$

**The number $a$ times the vector 0**: 

$a0 = a(0+0) = a0 + a0 \implies a0-a0 = a0 + a0-a0 \implies 0 = a0$

**The number -1 times a vector $v$**

$-1 v + 2v = (-1+2)v = v \implies -1v + 2v - 2v = v-2v \implies -1v = v - 2v $

$\implies -1v + 1v = v - 2v + 1v = 0 \implies v + (-2+1)v = 0 \implies v + -1v = 0$

*Suppose the Additive inverse of $v$ is $-v$* $\implies v + (-v) = 0 = v + -1v \implies -v = -1v$

## 1.C

**Subspace**

1.34:
**Conditions for a subspace**:

A subset $U$ of $V$ must satisfy these conditions:

A. *Additive identity*: $0 \in U$ (ensure the additive identity of $V$ is in $U$ )

B. *closed under addition*: $u, w \in U \implies u + w \in U$ (addition makes sense on $U$)

C. *closed under scalar multiplication*: $a\in F, u \in U \implies au \in U$ ($-u$ exists)

**1.36: Sum of subsets**

$U_1 + ...+U_m = \{u_1+...+u_m: u_1 \in U_1, ..., u_m \in U_m\}$

**1.38**： $U = \{(x, x, y, y) \in F^4: x,y \in F\}, W = \{(x, x, x, y) \in F^4: x,y \in F\}$

$U + W = (x_1 + x_2, x_1+x_2, y_1+x_2, y_1+y_2) \implies (x,x,y,z)$

**1.40 Direct Sum**: Suppose $U_1, ...,U_m$ are subspaces of $V$, every element of $U_1+...+U_m$ could be written in the form $u_1 + ...+u_m$, where each $u_j \in U_j$

**1.43 Example**: 
$$
U_1 = \{(x,y,0) \in F^3: x,y \in F\}\\
U_2 = \{(0,0,z) \in F^3: z \in F\}\\
U_3 = \{(0,y,y) \in F^3: y \in F\}
$$
$U_1 + U_2 + U_3 = F^3$

Consider this vector $(0,0,0)$

$(0,0,0) = (0,1,0) + (0,0,1) + (0,-1,-1) = (0,0,0)+(0,0,0)+(0,0,0)$

So, $U_1 + U_2, + U_3$ is not direct sum.
