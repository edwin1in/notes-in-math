Since we have been dealing with PMFs and PDFs, the Cumulative Distribution Function (CDF) describes both of them in one.  The CDF of a random variable $X$ is denoted as $F_{X}(x)$ and provides the probability $P(X \leq x)$.

$$
F_{X}(x) = P(X \leq x) = \begin{cases} \sum\limits_{k \leq x} p_{X}(k), \ \text{if $X$ is discrete}, \\ \int^{x}_{-\infty}f_{X}(t)dt, \ \text{if $X$ is continuous} \end{cases}
$$
If $X$ is discrete and takes integer values, the PMF and the CDF can be obtained from each other by summing or differencing.


$$
F_{X}(x) = \sum\limits_{i = -\infty}^{k}p_{X}(i)
$$
$$
p_{X}(k) = P(X \leq k) - P(X \leq k-1) = F_{X}(k) - F_{X}(k-1)
$$
If $X$ is continuous, the PDF and CDF can be obtained by integration or differentiation.
$$
F_{X}(X) = \int^{x}_{-\infty}f_{X}(t)dt
$$
$$
f_{X}(X) = \frac{dF_{X}}{dx}(x)
$$
### Geometric CDF 
Let $X$ be a geometric random variable with parameter $p$. That is, $X$ is the number of trials until the first success in a sequence of independent Bernoulli trials. The CDF is given by

$$
F_{geo}(n) = \sum\limits_{i=1}^{n}p(1-p)^{k-1}= 1-(1-p)^{n}
$$
### Exponential CDF 
Let $X$ be the exponential r.v. with parameter $\lambda > 0$. Its CDF is given by
$$
F_{exp}(x) = P(X \leq x) = 0,  \text{for $x \leq 0$},
$$
$$
F_{exp}(x) = \int^{x}_{0} \lambda e^{-\lambda t}dt = 1-e^{-\lambda x}
$$
### Standard Normal R.V. 
A normal random variable $Y$ with zero mean and unit variance is said to be a standard normal. Its CDF is denoted as

$$
\phi(y) = P(Y \leq y) = P(Y < y) = \frac{1}{\sqrt{2\pi}} \int^{y}_{-\infty} e^{\frac{-t^2}{2}}dt
$$
Generally,

$$
\phi(-y) = 1-\phi(y)
$$
Let $X$ be a normal random variable with mean $\mu$ and variance $\sigma^{2}$. We have "standardize" $X$ by defining a new random variable $Y$ given by

$$
Y = \frac{X-\mu}{\sigma}
$$
$$
E[Y] = \frac{E[X]-\mu}{\sigma} = 0
$$
$$
var(Y) = \frac{var(X)}{\sigma^{2}}=1
$$
### CDF calculation for a Normal r.v.
$$
P(X \leq x) = P\left(\frac{X-\mu}{\sigma} \leq \frac{x-\mu}{\sigma}\right)= P\left(Y \leq \frac{x-\mu}{\sigma}\right)= \phi(\frac{x-\mu}{\sigma})
$$
