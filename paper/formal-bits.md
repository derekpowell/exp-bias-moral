We let S be represented by a random vector X, whose members are any number of discrete events $x_1, x_2, ..., x_n$, where $x_i$ represents the event of interest so that $x_i$ occurs in S with some probability and occurs in S' with probability 1. That is, S represents $X$ and S' represents $X|x_i=1$. We write this as:

$V(x_i) = EU(X|x_i) - EU(X) =  \sum_{x \in X} U(x)p(x|x_i) - \sum_{x \in X} U(x)p(x)$

Applying the chain rule of probability and some algebra (see appendix) we eventually obtain:

$V(x_i) = \big(1 - p(x_i) \big) \sum_{x \in X} U(x)p(x|x_i) $

Thus, the value assigned to event $x_i$ is proportional to the prior probability of $x_i$. Further, this holds true regardless of the nature of the event in question and of the form of the utility function over events.



**Appendix**

$V(x_i) = EU(X|x_i) - EU(X) $ 

$V(x_i) =  \sum_{x \in X} U(x)p(x|x_i) - \sum_{x \in X} U(x)p(x)$ 	(LOTUS)

$V(x_i) = \sum_{x \in X} U(x)p(x|x_i) - \sum_{x \in X} U(x)p(x|x_i)p(x_i)$ 	( Chain rule of probability )

$V(x_i) = \sum_{x \in X} U(x)p(x|x_i) - p(x_i)\sum_{x \in X} U(x)p(x|x_i)$

$V(x_i) = \big(1 - p(x_i) \big) \sum_{x \in X} U(x)p(x|x_i) $



