# Exercise 1.A

Q1
$$
1/(a+bi) = c + di \\
\implies 1/a + 1/bi = c + di \\
\implies c = 1/a, di = 1/bi \\
\implies bi * di = 1 \\
\implies bd * -1 = 1 \implies bd = -1 \implies d = -1/b
$$

Q2
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

##### Q1

$-(-v) = v \iff -(-v) + (-v) = v + (-v) \iff -(-v) + (-v) = 0 \iff 0 = 0$

$0 = 0 $ is true, we get $-(-v) = v$.

##### Q2

Suppose $a \neq 0, v \neq 0$

$a \in F, v \in V, av = 0 \implies av -av = 0 - av \implies 0 = -av = av$

$\implies - av + av = av + av \implies 0 = (a+a)v = 2av \implies 2av = 0 = av$

$a \neq 0, v \neq 0,2av = av \implies 2a = a, v =v(not\ proved) \implies  2a - 1a = a - 1a \implies a = 0$ , which is contradicted with $a \neq 0, v \neq 0$, the set of all 4 possibilities is: $\{a \neq 0, b \neq 0; a = 0, b\neq 0; a\neq0,b=0; a = 0 , b=1\}$ and we could exclude one from the set and the remaining satisfy the lemma.

##### Q3

$v + 3x = w \implies v + 3x -v = w-v \implies 3x = w-v \implies x = \frac{1}{3}w - \frac{1}{3}v$

$\exist w',v' \in V,w' = \frac{1}{3}w, v' = \frac{1}{3}v;\ \exist v''\in V, v'' = - v'\implies \exist x \in V, x = w'+v''$

##### Q4

**1.19**: commutativity, associativity, additive identity, additive inverse, multiplicative identity, distributive properties

The empty set is failed to satisfy the property of additive inverse since there’s no element in $\empty$, so $0 \notin \empty$

Answer to confusion about antecedent and implication ($False \implies True$): <https://math.stackexchange.com/questions/4178665/the-empty-set-fails-to-satisfy-only-one-of-the-axioms-of-vector-spaces-which-on>

5.

$0v = 0,\forall v \in V$
$\implies 0(RHS) = (-1+1)v = -1v + 1v = -v + v$
$\implies 0v = -v + v$
$\implies 0v = 0$
$\implies 0 = -v + v$

6.

No: Suppose $I: \{\infin\} \cup \{-\infin\}, G: R \cup I\}$, and definition of sum and “$0$” are same as $R$'s, consider this case:

$1 + \infin + (-\infin) = \infin + (-\infin) = 0$

$1 + (\infin + (-\infin)) = 1+0 = 1 \neq 0$

It doesn’t satisfy the property of associativity, so its not.

# Exercise 1.C

##### Q2

*(a)*: $\{(x_1, x_2, x_3, x_4)\in F^4: x_3=5x_4 + b \}$ is not subspace of $F^4$ when $b\ne 0$

**Counter-example:** suppose $u = (x_1, x_2, x_3, x_4)$

$u+u = (2x_1, 2x_2, 2x_3, 2x_4) = (x_1', x_2', x_3', x_4')$

we know $x_3=5x_4 + b \implies x_3' = 2x_3 = 10x_4 + 2b$

and also $x_3' = 5x_4' + b \implies 2x_3 = 5*(2x_4) + b = 10x_4 + b \neq 10x_4 + 2b\ since\ b \neq 0$, and which is contradicted.

*(b)*:

Prove the set of continuous real-valued functions on the interval $[0,1]$ is a subspace of $R^{[0,1]}$

$F: \{[0,1] \to \R \}$:

**1. Additive Identity**: $f \in F, f: [0,1] \to 0$

**2. close under addition:** Suppose $f, g \in F$, and $h = f+g$

$f, g \in F, f,g: [0,1] \to \R， h: [0,1]\to \R + \R = \R$

we also want to prove when $f, g$ are continuous, $h=f+g$ is continuous.

$f,g$ are continuous $\iff$ $\forall x \in [0,1], \lim_{x' \to x}{f(x')}=f(x), \lim_{x' \to x}{g(x')}=g(x)$

$\forall x \in [0,1], h(x) = f(x) + g(x) \in \R$

$\implies \forall x \in [0,1], \lim_{x' \to x}{h(x')} = \lim_{x' \to x}{f(x')} + \lim_{x' \to x}{g(x')}$

$\implies = f(x) + g(x) = h(x)$

$\forall x \in [0,1], h(x) = \lim_{x' \to x}{h(x')} \iff h$ is continuous.

**3. closed under scalar multiplication**: similar with second item

##### Q3

**Additive identity**: $0 \in f, 0: 0(x) = 0$, $0'(x) = 0 \implies 0'(-1) = 3(0(2)) $

**Close under addition**: $u,w \in f, u,w: (-4,4) \to \R$

$(u + w)(x) = u(x) + w(x) \in \R + \R = \R$

$(u+w)'= u'+w' \implies (u+w)'(-1) = u'(-1) + w'(-1) = 3(u(2))+3(w(2))$

$= 3(u(2)+w(2)) = 3((u+w)(2))$

So, $(u+w)'(-1) = 3((u+w)(2))$

**Closed under scalar multiplication**: Suppose $a \in \R, u \in f$

$au: (-4,4) \to a\R = \R $

$(au)'(-1) = a(u'(-1)) = a(3u(2)) = 3au(2) = 3(au(2))$

Q4.

$f: {[0,1] \to R}$, and ${f: \int_0^1 f = b}$

**Known**: $f$ is a subspace of $R^{[0,1]}$

Additive id exists: $0 \in f,f_0: 0(x) = 0, \int_0^1 f = 0 = b$

##### Q5

*Closed multiplication is not satisfied*:

$a \in I, x \in R \implies ax \in I, ax \notin R$

##### Q6

**No.**

$A:\{(a,b,c)\in \R^3, a^3=b^3\}$

Since $a,b\in R, a^3 = b^3 \iff a = b$

$\implies A:{(a,b,c)\in \R^3, a=b}$

*Closed Addition*: $u,w \in A, u = (a_1, b_1, c_1), w = (a_2, b_2, c_2), a_1 = b_1, a_2=b_2$

$u + w = (a_1 + a_2, b_1 + b_2, c_1 + c_2), a_1 + a_2 = b_1+b_2$

*Closed Multiplication*:

$k \in F, u \in A, u = (a,b,c)$

$k\in I \implies ku = (ka,kb,kc) \notin \R^3$

**No.**

$A:{(a,b,c)\in C^3, a^3=b^3}$

Consider this case:
$p,q \in A$
$p = (\sqrt{3} + i, -\sqrt{3}+i, 0), (\sqrt{3} + i)^3 = (-\sqrt{3}+i)^3 = 8i$
$q = (\sqrt{3} + i, -2i, 0), (\sqrt{3} + i)^3 = (-2i)^3 = 8i$
$p+q = (2\sqrt{3} + 2i, -\sqrt{3}-i, 0)$
$(2\sqrt{3} + 2i)^3 = 64i,  (-\sqrt{3}-i)^3 = -8i, 64i \ne -8i$
$\implies p+q \notin A$

##### Q7

Consider this case:
$U: \{(p,q), p,q\in [-1,1]\}$
$u \in U: a < -1, a > 1 \implies au \notin U$

##### Q8

$U: \{(p,q), p,q \neq 0\}$
There is no additive identity in $U$.

##### Q9

Suppose $Q$ is the set of all $f$.

*Additive Id*:
$0\in Q, 0(x) = 0, x \in \R \implies p \in \R^+, x+p \in \R, 0(x+p) = 0 = 0(x)$

*Closed Add*:
$f,g \in Q, f(x+p) = f(x), g(x+p) = g(x)$
$(f+g)(x) = f(x)+g(x), (f+g)(x+p) = f(x+p)+g(x+p) = f(x) + g(x)$

*Closed Mul*:
$a \in F, f \in Q, af(x) \in R$
$af(x+p) = a(f(x+p)) = a(f(x)) = af(x)$

##### Q10

*Additive Id*:

$\{0\}\in U_1 \cap V, \{0\}\in U_2 \cap V \implies \{0\}\in U_1 \cap U_2$

*Closed Addition*: $U_1, U_2 \in V, \forall u_1, u_2 \in U_1 \cap U_2 \implies u_1 + u_2 \in U_1 \wedge u_1 + u_2 \in U_2 \iff u_1+u_2 \in U_1 \cap U_2$

*Closed Multiplication*:

$a\in F, u \in U_1 \cap U_2 \implies  au \in U_1 \wedge au \in U_2 \implies au \in U_1 \cap U_2$

##### Q11

Based on the result from Question 10, by induction, we could prove that.

##### Q12

Suppose $U_1, U_2$ are subspaces of $V$

Assume $U_1 \cup U_2$ is a subspace of $V$ when $U_1 \notin U_2$ or $U_2 \notin U_1$

$U_1 \notin U_2 \land U_2 \notin U_1\implies $

$U_1' = U_1 \setminus (U_1 \cap U_2) \ne \empty$

$U_2' = U_2 \setminus (U_1 \cap U_2) \ne \empty$

Consider $u_1 \in U_1', u_2 \in U_2'$

And we know $U_1' \in U_1, U_2' \in U_2' \implies U_1', U_2' \in U_1 \cup U_2$ by definitions of $U_1', U_2'$.

$\implies u_1 \in U_1, U_2\in u_2;\ u_1, u_2 \in U_1 \cup U_2$

$U_1 \cup U_2$ is a subspace of $V \implies u_1 + u_2 \in U_1 \cup U_2$

$\implies u_1+u_2 \in U_1 \lor u_1 + u_2 \in U_2$

If $u_1+u_2 \in U_1 \iff u_1, u_2 \in U_1$ by the property of Closed Addition for $U_1$, which is contradicted with $u_2 \in U_2'$ since $U_2' \cap U_1 = \empty$. So, $u_1 + u_2 \notin U_1$.

If $u_1+u_2 \in U_2 \iff u_1, u_2 \in U_2$ by the property of Closed Addition for $U_2$, which is contradicted with $u_1 \in U_1'$ since $U_1' \cap U_2 = \empty$. So, $u_1 + u_2 \notin U_2$.

$\implies u_1 + u_2 \notin U_1 \cup U_2$, so the assumption is false.  $\implies U_1 \in U_2$

##### Q13

Suppose the union of three subspaces of $V$:  $U_1, U_2, U_3$ is a subspace of $V$, based on the result from *Q12*:

$U_1 \cup U_2 \cup U_3 = (U_1 \cup U_2) \cup U_3$ is a subspace of $V$

If $U_1 \cup U_2$ is a subspace of $V$:

$\implies U_1 \cup U_2 \in U_3$ or $U_3 \in U_1 \cup U_2$ (By *Q12*)

If $U_1 \cup U_2 \in U_3$, then it is satisfied that one of the subspaces contains the other two.

If $U_3 \in U_1 \cup U_2$, By *Q12*: When $U_1 \in U_2 \implies U_3 \in U_2, U_1 \in U_2$, satisfied.

If $U_1 \cup U_2$ is not a subspace of $V$ $\iff$ $U_1 \notin U_2$ and $U_2 \notin U_1$

$(U_1 \cup U_2) \cup U_3$ is a subspace of $V$

$\implies ID: \exist 0 \in (U_1 \cup U_2 \cup U_3)$

$\implies ADD:\exist u_1, u_2 \in (U_1 \cup U_2 \cup U_3), u_1 + u_2 \in (U_1 \cup U_2 \cup U_3)$

$U_1 \notin U_2 \land U_2 \notin U_1\implies$

$U_1' = U_1 \setminus (U_1 \cap U_2) \ne \empty$

$U_2' = U_2 \setminus (U_1 \cap U_2) \ne \empty$

Consider $u_1 \in U_1', u_2 \in U_2$ *(Definition of $u_2$ is different from Q12)*

$\implies u_1 + u_2 \notin U_1 \cup U_2 \land u_1+u_2\in U_1 \cup U_2\cup U_3 \implies u_1 + u_2 \in U_3$

Consider $u_1$ is an arbitrary element in $U_1'$

**TODO...**

##### Q14

Suppose $u \in U, u=(x_1,x_1,y_1,y_1), w \in W, w=(x_2,x_2,x_2,y_2) $

$\implies u+w = (x_1+x_2,x_1+x_2,y_1+x_2, y_1+y_2)$

Suppose $x,y,z = x_1+x_2,y_1+x_2, y_1+y_2$.

$\forall x\in F, \exist (x_1 + x_2) \in F$

$\forall y\in F, \exist (y_1 + x_2) \in F$

$\forall z\in F, \exist (y_1 + y_2) \in F$

$\implies x,y,z \in F$

$u+w - (x,x,y,z) = 0 \implies u+w = (x,x,y,z)$

##### Q15

It is a set containing results of the sum for all pairs of two arbitrary elements in $U$. Suppose $u \in U, u' \in U, u+u' \in U$ since $U$ is under closed addition, which means this set is still $U$.

##### Q16

Suppose $u \in U, w \in W ; U,W\in V \implies u,w\in V$

$U+W = \{u+w\}$

Because $u,w \in V \implies u+w = w+u$ by the commutative property of $V$.

$\implies U+W = \{u+w\} = \{w+u\}$

##### Q17

Similar with Q16

##### Q18

Yes, and the additive identity of subspaces $0_s$ is the set containing one element that is the additive identity of $V$. 

Consider $U$ is a subspace of $u \in U, w \in 0_s, u + w = u+0 = u$ 

Only $0_s$ has the additive inverses. 

Suppose $U, W$ are subspaces of $V$, and $U + W = {0}$ and $U$ are not $0_s$.

$U+W = \{u \in U, w \in W;u+w\}$

It could be proved as a false statement by an example:

$U + W = {0} \iff \forall u \in U, \forall w \in W, u+w = 0$

By the property of the subspace $U$: $\exist u' \in U, u' \neq 0 \implies u +u' \in U$

$\implies u+w+u' = (u+u') + w \in U+W$

And we know $(u+u') + w = u' \ne 0 \iff U + W \neq {0}$, so it is contradicted.

As a result we know $U = 0_s$

##### Q19

~~Yes~~. **This answer is wrong, TODO..**

We assume $U_1 = U_2$, and we know $U_1 + W = U_2 + W$

$\iff \{\forall u_1 \in U_1, \forall w \in W; u_1 +w\} = \{ \forall u_2 \in U_2, \forall w \in W; u_2 +w\}$

$\iff \{\forall u_1 + w, \forall u_2 + w, u_1 + w = u_2 + w\}$

$u_1 + w = u_2 + w \iff u_1 = u_2$

$\implies \forall u_1 , \forall u_2 , u_1 = u_2 \iff U_1 = U_2$

##### Q20

$U = \{(x,x,y,y) \in F^4 \}$

~~A trivial solution is the subspace $0 \in F^4$~~

Consider $W = \{(0,0,z,0)\} \in F^4$

$U+W = \{(x,x,y+z,y)\}$

We want to prove $U + W = 0 \iff x = 0, y = 0, z = 0$

Consider $v =u+w= (x,x,y+z,y)$

$x,y,z=0\implies v=0;$

**Uniqueness**: Suppose $v' =u'+w' = (x',x',y'+z, y')=0$

$v' - v = 0 = (x-x', x-x', y+z-y'-z', y-y')$

$\implies x=x', y=y' \implies y+z-y'-z' = y-y' +z-z' = z-z'$ 

We know $z-z' = 0 \implies z=z' =0$

##### Q21

$U=\{(x,y, x - y, x + y, 2x)\in F^5\}$

Consider $W = \{(0,0,a,a,0) \in F^5 \}$

$u \in U, u = (x,y,x-y,x+y,2x), w \in W, w = (0,0,a,a,0)$

$v: x,y,a=0 \implies u+w = 0 = (x,y,x-y+a,x+y+a,2x) $

**Uniqueness**: Suppose $v': u'+w' = (x',y',x'-y'+a',x'+y'+a', 2x') = 0$

$v-v'$

$= (x-x', y-y', x-y+a - (x'-y'+a'), x+y+a-x'-y'-a', 2x-2x')$

$=0$

$\implies x = x'=0, y = y'=0$

$\implies x-y+a-(x'-y'+a') = a-a' = 0$

$\implies a = a' = 0$

##### Q23

Consider this counter-example:

$U = \{(x,0) \in \R^2\}, W = {(0,y) \in \R^2}, W = \{(z,z) \in \R^2\}$

##### Q24

$U_e: \{e: \R \to \R, e(-x) = e(x), x \in \R \}$

$U_o: \{o: \R \to \R, o(-x) = -o(x), x \in \R \} $

$U_e \oplus U_o: \{e+o\} \in \R^\R$

$0 = (e+o)(-x) = e(-x) + o(-x) = e(x) - o(x)$

$0 = e(x) - o(x) \implies e(x) = o(x) = -o(-x) = e(-x)$

$e(x) = o(x) \implies -o(-x) = -e(-x) \implies e(-x) = -e(-x)$

$\iff e = 0 \implies e= o = 0$.  We proved only when $e,o =0$, $u \in U_e+U_o, u = 0$

So, $U_e + U_o = U_e \oplus U_o$



 $U_e \oplus U_o \implies U_e \cap U_o = \{0\}$

We want to prove $U = U_e \oplus U_o = \R^\R$

$u \in U_e \oplus U_o, u = e+o, u(x) = e(x) + o(x) $

$f \in \R^\R, f(x) \in \R$

We want to prove $\forall f \in \R^\R, \exist u \in U \land \forall u \in U, \exist f \in \R^\R$, 

$f \in \R^\R, f : \R \to \R, $

$u = e+o, u \in U$

Consider $f = e' = \frac{e}{2}; o' = -\frac{o}{2} $, and we could see $e’ \in U_e,  o’ \in U_o,$

$e' + o' = \frac{e-o}{2} \implies (e'+o')$

**TODO…**
