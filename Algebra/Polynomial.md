A *Polynomial* is an algebraic expression consisting of a sum of *terms*.

*Terms* are of the form:
$$cx^i$$
Where $c$ is a constant called a *coefficient* and $x$ is a *variable*, raised to a non-negative integer $i$.

## Examples

$$x^2 + 4x + 5$$
$$-3d^4$$
$$y^3+5y$$
$$2o$$
$$6$$
(The last example is equivalent to $6x^0$).

Polynomials of one term are also usually called [[Monomial]]s and polynomials of two terms are usually called [[Binomial]]s. There's also the term [[Trinomial]] for polynomials of three terms, but we usually just call them Poly-* for any polynomial with more than two terms. 

## Definitions

For a polynomial $f$ and a real number $k$, the following statements are equivalent:
* $x = k$ is a **root**, or solution, of the equation $f(x) = 0$,
* $k$ is a **zero** of function $f$,
* $(k, 0)$ is an $x$-intercept of the graph $y = f(x)$,
* $x-k$ is a linear factor of $f(x)$.

Let's understand this with the polynomial $g(x) = (x-3)(x+2)$, which can be written as $g(x)=(x-3)(x-(-2))$.

First, we see that the linear factors of $g(x)$ are $(x-3)$ and $(x-(-2))$.

If we set $g(x) = 0$ and solve for $x$, we get $x = 3$ or $x = -2$. These are the solutions, or **roots**, of the equation.

A **zero** of a function is an $x$-value that makes the function value $0$. Since we know $x = 3$ and $x = -2$ are solutions to $g(x) = 0$, then $3$ and $-2$ are zeros of function $g$.

Finally, the $x$-intercepts of the graph $y=g(x)$ satisfy the equation $0 = g(x)$, which was solved above. The $x$-intercepts of the equation are $(3,0)$ and $(-2,0)$.

## Polynomial Arithmetic

### Addition
To *add* two polynomials, we *add* the like terms together.

If for a certain degree one of two addends doesn't have a term of that degree, we just copy that term to the final sum.

$$
\begin{aligned}
(x^2 + 4x + 5) + (x^3 + 5x)\\
x^2 + 4x + 5 + x^3 + 5x\\
x^2 + 9x + 5 + x^3\\
x^3 + x^2 + 9x + 5
\end{aligned}
$$

### Subtraction
To *subtract* two polynomials, we can distribute the $-$ sign (or multiply everything by $-1$) to the terms of the second polynomial and then perform addition as per usual.

$$\begin{aligned}
(w^2 + 2w + 5) - (w^3 - 4w)\\
w^2 + 2w + 5 - w^3 + 4w\\
w^2 + 6w + 5 - w^3\\
-w^3 + w^2 + 6w + 5
\end{aligned}
$$

## End Behaviour

See [[End Behaviour]]