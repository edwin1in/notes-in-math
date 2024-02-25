Given two r.v.s $X$ and $Y$ (within the same domain $\Omega$), their joint PMF is

$$
P_{X,Y}(x,y) = P(X=x, Y=y) = P(\set{X=x} \cap \set{Y=y})
$$
We denote the marginal PMFs as $P_{X}(x)$ and $P_{Y}(y)$ to distinguish from joint PMFS. To calculate each marginal PMFs,

$$
P_{X}(k) = \sum\limits_{y} p_{X,Y}(k,y)
$$
$$
P_{Y}(k) = \sum\limits_{x}p_{X,Y}(x,k)
$$
Consider this. Let the range($X$) $= \set{1,2,3,4}$. Then the sample space is just a partition of $\set{X=1} \cup \set{X=2}\cup \set{X=3}\cup \set{X=4} = \Omega$. These events are disjoint. Now consider the range($Y$) $= \set{1,2,3}$. Suppose that another event intersects the partitioned sample space. Let's say $\set{Y=3}$. Then 

$$
P(Y = 3) = P(X=1,Y=3) +P(X=2,Y=3) + ...
$$
