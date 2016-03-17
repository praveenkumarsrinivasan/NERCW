
-----

### LDA - Dirichlet Parameter
<hr/>

- Latent Dirichlet Allocation (LDA) allocates topics using a Dirichlet distribution
- LDA Model depend on the Dirichlet parameter
- The Dirichlet distribution has a parameter must be estimated
- Dirichlet parameter controls the shape of the distribution; hence the likelihood of a topic being selected
-----
- High value lead to many topics being associated to each term
- Low value leads to only a few topics being associated to each term
- Generally all parameters are set to be equal; each document has the same likelihood for all topics
- Small values lead to only a few topics allocated to each document

---

### What is latent?
<hr/>

- We observe documents(words) but all the other variables(topics, topic proportions, topic assignment) are **latent**
-----

### Bayes Theorem
<hr/>

$$
p(T|W) = \frac{p(W \cap T)}{p(W)} = \frac{p(T) . p(W|T)}{p(W)}
$$

Notes:
- why lda is a generative model and a inverse method?
    + it is a generative model but it can be to inverse the procedure through Bayesian framework.
    + it use Dirichlet prior to do the same

---
