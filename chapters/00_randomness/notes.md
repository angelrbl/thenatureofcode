# Chapter 0: Randomness

### Random walks
Can be summarized as: 
- simulate decisions based on pure randomness.
- At any moment, the probability that one decision is taken is the same as any other one. (as for the walker example)
- random() produces a uniform distribution.

---

### Probability and Nonuniform Distributions
The main objective is to produce nonuniform distribution of random numbers, where some outcomes are more likely than others. \
Probability of the fittest: Darwininian natural selection. \
Nonuniform distributions with random():
- fill an array with numbers, some of them are the same
```
    let stuff = [1, 1, 2, 3, 3];
    let value = random(stuff);
```