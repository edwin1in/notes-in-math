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
Thus the variance can be computed like this
$$
\begin{align*}\\
\\ var(X) &= E[(X-E[X])^{2}] = \sum\limits_{x}(X-E[X])^2p_{X}(x) 
\end{align*}
$$
Similarly, the $n$-th moment is given by
$$
\begin{align*}\\
\\ E[X^{n}] &= \sum\limits_{x}x^{n}p_{X}(x)
\end{align*}
$$
