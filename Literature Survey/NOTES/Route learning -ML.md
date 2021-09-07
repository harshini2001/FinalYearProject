# Introduction

- ML based approach to infer customer constraints.
- Bayesian network=> type of graphical model convenient to establish parent-child structures.
- proposed a probabilistic directed graphical model=> Metropolis-Hastings-within-Gibbs sampling algorithm.

---

## Model definition

- constraints can cause customers to flip.

- the flip has two causes
  - effect of other customers' time windows on the route sequence.
  - customer inhernet constraints.

![image](https://user-images.githubusercontent.com/60444216/132233105-2a855803-1cfb-413c-a407-4acb7eb63d4b.png)


---

## Factors

- customer time windows
- traffic congestion
- zone access restrictions
