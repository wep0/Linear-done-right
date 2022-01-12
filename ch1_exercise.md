# Exercise 1.A

1.
$$
1/(a+bi) = c + di \\

\implies 1/a + 1/bi = c + di\\

\implies c = 1/a, di = 1/bi \\

\implies bi * di = 1 \implies bd * -1 = 1 \implies bd = -1 \implies d = -1/b\\
$$
2.
$$
(\frac{-1+\sqrt{3}i}{2})^3 \\
= \frac{(1-2\sqrt3i - 3) *(-1+\sqrt3 i)}{8} \\
= \frac{(-1+2\sqrt{3}i + 3) + (\sqrt{3}i + 6 - 3\sqrt{3}i)}{8} \\
= \frac{2+6}{8}  = 1\\
$$


3.
$$
i = f^2, f\in F\\
let\ f = a + bi\\
i = (a + bi)^2 = a^2 + 2abi - b^2\\
i = (a^2 - b^2) + 2abi\\
\left\{
\begin{aligned}
a^2 - b^2 = 0 \\
2ab = 1 \\
\end{aligned}
\right.\\
a = b: 2a^2 = 1, a=\pm \frac{\sqrt{2}}{2}\\
a = -b: -2a^2 = 1, a = \sqrt{-\frac{1}{2}}
$$
The two sqrts are $\pm \frac{\sqrt{2}}{2}$

4.
$$
\alpha: a + bi, \beta: a' + b'i; \forall \alpha, \beta \in C\\
\alpha + \beta = a+a' + (b+b')i = \beta + \alpha
$$
5.

6.



10.
$$
x \in R^4, st. (4,-3,1,7) + 2x = (5,9,-6,8)\\
2x = (1, 12, -7, 1)\\
x = (1/2, 6, -7/2, 1/2)
$$
11.



# Exercise 1.B

1.

$-(-v) = v \iff -(-v) + (-v) = v + (-v) \iff -(-v) + (-v) = 0 \iff 0 = 0$

$0 = 0 $ is true, we get $-(-v) = v$.

2.

Suppose $a \neq 0, v \neq 0$

$a \in F, v \in V, av = 0 \implies av -av = 0 - av \implies 0 = -av = av$

$\implies - av + av = av + av \implies 0 = (a+a)v = 2av \implies 2av = 0 = av$

$a \neq 0, v \neq 0,2av = av \implies 2a = a, v =v(not\ proved) \implies  2a - 1a = a - 1a \implies a = 0$ , which is contridicted with $a \neq 0, v \neq 0$, the set of all 4 possiblities is: $\{a \neq 0, b \neq 0; a = 0, b\neq 0; a\neq0,b=0; a = 0 , b=1\}$ and we could exclude one from the set and the remainings satisfy the lemma.

3.

$v + 3x = w \implies v + 3x -v = w-v \implies 3x = w-v \implies x = \frac{1}{3}w - \frac{1}{3}v$

$\exist w',v' \in V,w' = \frac{1}{3}w, v' = \frac{1}{3}v;\ \exist v''\in V, v'' = - v'\implies \exist x \in V, x = w'+v''$

4.

**1.19**: commutativity, associativity, additive identity, additive inverse, multiplicative identity, distributive properties

The empty set is failed to satisfy the property of additive inverse since there’s no element in $\empty$, so $0 \notin \empty$

Answer to confusion about antecedent and implication ($False \implies True$): https://math.stackexchange.com/questions/4178665/the-empty-set-fails-to-satisfy-only-one-of-the-axioms-of-vector-spaces-which-on



5.
$$
0v = 0,\forall v \in V\\
\implies 0(RHS) = (-1+1)v = -1v + 1v = -v + v\\
\implies 0v = -v + v\\
\implies since\ 0v = 0\\
\implies 0 = -v + v
$$


6.

No: Suppose $I: \{\infin\} \cup \{-\infin\}, G: R \cup I\}$, and definition of sum and “$0$” are same as $R$'s, consider this case:

$1 + \infin + (-\infin) = \infin + (-\infin) = 0$

$1 + (\infin + (-\infin)) = 1+0 = 1 \neq 0$

It doesn’t satisfy the property of associativity, so its not.
