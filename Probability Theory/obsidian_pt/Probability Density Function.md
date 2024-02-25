Suppose that we have a subset $S \subseteq \mathbb{R}$. Then a random variable $X$ is continuous iff there's a **non-negative** function $f_{X}$ , called the probability density function or PDF, such that 

$$
P(X \in S) = \int_{S}f_{X}(x)dx
$$
>[!note] 
>Function must be non-negative for every $x$ for it to qualify to be a valid PDF.

If we have an interval as our subset then

$$
P(a \leq X \leq b) = \int^{b}_{a} f_{X}(x)dx
$$
For $P(X=a)$, we have 

$$
P(X=a) = \int^{a}_{a} f_{X}(x)dx = 0
$$
Thus including/excluding the endpoints have no effect on its probability. Then that means that
$$
P(a \leq X \leq b) = P(a < X \leq b) = P(a \leq X < b) = P(a < X < b)
$$
Similar to the PMF, it must add up to one.
$$
P(-\infty < X < \infty) = \int^{\infty}_{-\infty}f_{X}(x)dx = 1
$$

### Continuous Uniform Random Variable 

Assume that we have an interval $[a,b]$ and probability is uniform. Then we have some constant for the PDF.

$$
f_{X}(x) = \begin{cases} c, \ \text{if $a \leq 0 \leq b$} \\ 0, \text{otherwise}\end{cases}
$$
It can be determined using the normai
