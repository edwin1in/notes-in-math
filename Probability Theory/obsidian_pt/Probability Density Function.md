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
f_{X}(x) = \begin{cases} c, \ \text{if $a \leq x \leq b$} \\ 0, \text{otherwise}\end{cases}
$$
It can be determined using the normalization property. 

$$
1 = \int^{\infty}_{-\infty}f_{X}(x)dx = \int^{b}_{a}cdx, c = \frac{1}{b-a}
$$
Thus if our random variable is uniform then, 
$$
f_{X}(x) = \begin{cases} \frac{1}{b-a}, \ \text{if $a \leq x \leq b$} \\ 0, \text{otherwise}\end{cases}
$$

### Exponential Random Variable 
A exponential random variable has a PDF in the form of 

$$
f_{X}(x) = \begin{cases} \lambda e^{-\lambda x}, \ \text{if $x \geq 0$,} \\ 0, \ \text{otherwise}\end{cases}
$$
An exponential random variable can be a good model for the amount of time until an incident of interest takes place.

The expected value of an exponential random variable is 
$$
E[X] = \frac{1}{\lambda}
$$
The 2nd moment is 


