The probability mass function or PMF takes a value and gives the probability of the event that the [[Random Variable]] is equal to that value. Namely,
$$
\begin{align*}\\
\\ p_{X}(x) &= P(\set{X=x}) = P(X=x)
\end{align*}
$$
For the probability that $X$ takes on a value within the set $S$.
$$
\begin{align*}\\
\\ P(X \in S)
\end{align*}
$$
Note that 

$$
\begin{align*}\\
\\    \sum_{x} p_{X}(x) &= 1
\end{align*}
$$
Where $x$ ranges over all the possible numerical values of $X$.

### [[Bernoulli Random Variable]]
The Bernoulli Random Variable takes on two values. Success or failure , 1 or 0, etc.
A random variable of flipping a coin is 

$$
\begin{align*}\\
 X &= \begin{cases} 1, \text{if heads} \\ 0, \text{if tails}\end{cases}
\end{align*}
$$
Let say that the probability of flipping a head is $p$, then the probability of flipping a tail is $1 - p$. The PMF will look like this.
$$
\begin{align*}\\
\\ p_{X}(x)=\begin{cases} p \ , \text{if } x = 1 \\ 1-p\ , \text{if }x = 0 \end{cases}
\end{align*}
$$
### [[The Binomial Random Variable]]
Let $X$ be a binomial random variable with parameters $n$ and $p$. Where $n$ is the number of something (like the number of times flipping a coin) and $p$ is the probability of success (like the probability of heads). Then the PMF of $k$ successes is

$$
\begin{align*}\\
\\   p_{X}(k) &= {n \choose k} p^{k} (1-p)^{n-k}\ , \ k= 0,1,2,..., n
\end{align*}
$$
### [[The Geometric Random Variable]]
The geometric random variable is the number $X$ of tosses needed for one success. Let $p$ be the probability of success and $k$ be the number of tries until the first success.

$$
\begin{align*}\\
\\  p_{X}(k) &= (1-p)^{k-1}p \ , \ k = 1,2,...
\end{align*}
$$

### [[The Discrete Uniform Random Variable]]
Suppose that $a,b \in \mathbb{Z}$ and $X$ di

