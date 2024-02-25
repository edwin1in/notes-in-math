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