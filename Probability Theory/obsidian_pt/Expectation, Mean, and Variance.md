### Discrete 

The **expectation** of $X$ is the weighted (in proportion to the probabilities) average of the possible values of $X$.

Suppose that you spin a wheel $k$ times a let $m_{i}$ be the amount of money you win at the $i$-th position. Then the average money that you gain will be.  Let $k_{i}$ be the amount of spins that land on the $i$-th position.

$$
\begin{align*}\\
\\\ M &= \frac{m_{1}k_{1}+ m_{2}k_{2}+...}{k}
\end{align*}
$$
Since $\frac{k_{i}}{k} \approx p_{i}$ then we can say $M = m_{1}p_{1}+m_{2}p_{2}+...$ Then we can say for the expected value to be 

$$
\begin{align*}\\
\\E[X] &= \sum\limits_{x}xP_{X}(x)
\end{align*}
$$
The $n$-th moment of a random variable $X$ is the expected value of $X^n$.
$$
\begin{align*}\\
\\ E[X^n]\\
\end{align*}
$$
The **variance** of a random variable $X$ is denoted as $var(X)$. It is the expected value of the random variable $(X-E[X])^2$. It provides a measure of dispersion of $X$ around its mean.

$$
\begin{align*}\\
\\ var(X) &= E[(X-E[X])^2]
\end{align*}
$$
Since $(X-E[X])^{2}\geq 0$, then $var(X) \geq 0$. 

Another measure of dispersion is the **standard deviation** of $X$.
$$
\begin{align*}\\
\\
\\ \sigma_{X} &= \sqrt{var(X)}
\end{align*}
$$
Suppose that we have a function of a random variable $X$, $g(X)$. Then 
$$
\begin{align*}\\
\\ E[g(X)] &= \sum\limits_{x}g(x)p_{X}(x)
\end{align*}
$$
Similarly, the $n$-th moment is given by
$$
\begin{align*}\\
\\ E[X^{n}] &= \sum\limits_{x}x^{n}p_{X}(x)
\end{align*}
$$
Thus the variance can be computed like this
$$
\begin{align*}\\
\\ var(X) &= E[(X-E[X])^{2}] = \sum\limits_{x}(x-E[X])^2p_{X}(x) 
\end{align*}
$$
There is a much simpler way to define the $var(X)$:
$$
\begin{align*}\\
\\ var(X) &= E[X^2]-(E[X])^2
\end{align*}
$$
*Proof*:
$$
\begin{align*}\\
\\ var(X) &= \sum\limits_{x}(x - E[X])^2p_{X}(x)\\
&= \sum\limits_x(x^{2}-2E[X]x + (E[X])^2)p_{X}(x)\\
&= \sum\limits_{x}(x^{2}p_{X}(x)-2E[X]xp_{X}(x)+ (E[X])^2p_{X}(x))\\
&= \sum\limits_{x}x^{2}p_{X}(x)-\sum\limits_{x}2E[X]xp_{X}(x)+\sum\limits_{x}(E[X])^2p_{X}(x)\\
&= E[X^{2}] - 2E[X]\sum\limits_{x}xp_{X}(x) + (E[X])^2\sum\limits_{x}p_{X}(x)\\
&= E[X^{2}] - 2(E[X])^{2} + (E[X])^{2}\\
&= E[X^{2}]-(E[X])^2
\end{align*}
$$
Let $Y = aX + b$, then $var(Y) = a^2var(X)$
*Proof*:
$$
\begin{align*}\\
\\var(Y) &= E[Y^{2}] - (E[Y])^2\\
&= \sum\limits_{x}(g(x))^{2}p_{X}(x) - (\sum\limits_{x}g(x)p_{X}(x))^2\\
&= \sum\limits_{x}(ax+b)^{2}p_{X}(x) - (\sum\limits_{x}(ax+b)p_{X}(x))^2\\
&= \sum\limits_{x}(a^{2}x^{2}+2abx+b^{2})p_{X}(x) - (a\sum\limits_{x}xp_{X}(x)+b\sum\limits_{x}p_{X}(x))^2\\
&= a^{2}\sum\limits_{x}x^{2}p_{X}(x) + 2ab\sum\limits_{x}xp_{X}(x) + b^{2}\sum\limits_{x}p_{X}(x) - (aE[X]+b)^{2}\\
&= a^{2}E[X^{2}]+2abE[X] + b^{2}- (a^{2}E[X]^{2} + 2abE[X] + b^{2})\\
&= a^{2}(E[X^{2}]-(E[X])^{2})\\
&= a^{2}(var(X))
\end{align*}
$$

### Expectation and Variance of Known r.v.

#### Bernoulli r.v.
By the Bernoulli r.v. 
$$
\begin{align*}\\
\\ X &= \begin{cases} 1, \ \text{if success} \\ 0,\ \text{if failure}\end{cases}
\end{align*}
$$
The PMF of the Bernoulli r.v.
$$
\begin{align*}\\
\\ p_{X}(x) &= \begin{cases} p, \ \text{if $x=1$} \\ (1-p), \ \text{if $x=0$}\end{cases}
\\
\end{align*}
$$
Then the expected value is 
$$
\begin{align*}\\
\\ E[X] &= \sum\limits_{x}xp_{X}(x)\\
 &= (1)(p) + (0)(1-p) \\
&= p
\end{align*}
$$
The second moment is

$$
\begin{align*}\\
\\ E[X^{2}] &= \sum\limits_{x}g(x)p_{X}(x)\\
&= (1)^{2}p + (0)^{2}(1-p)\\
&= p
\end{align*}
$$

Then the variance of the Bernoulli r.v. is 

$$
\begin{align*}\\
\\
\\var(X) &= E[X^{2}] - (E[X])^{2}\\
&= p - p^{2}\\
&= p(1-p)
\end{align*}
$$
#### Discrete Uniform r.v. 

$$
E[X] = \frac{a+b}{2}
$$
## Continuous 
The expected value of a [[Probability Density Function]] is similar to that of a PMF.
Namely,

$$
E[X] = \int^{\infty}_{-\infty} xf_{X}(x)dx
$$
Suppose we have a function of a random variable, then the expected value is
$$
E[g(X)] = \int^{\infty}_{-\infty}g(x)f_{X}(x)dx
$$
The variance is 
$$
var(X) = E[(X-E[X])^{2}] = \int^{\infty}_{-\infty}(x-E[X])^{2}f_{X}(x)dx= E[X^{2}] - (E[X])^{2} 
$$
Suppose that we have a function of a random variable $Y = aX + b$ and $a,b$ are scalars.
Then 
$$
E[Y] = aE[X] + b 
$$
$$
var(Y) = a^{2}var(X)
$$