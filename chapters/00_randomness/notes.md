# Chapter 0: Randomness

### Random walks
Can be summarized as: 
- simulate decisions based on pure randomness.
- At any moment, the probability that one decision is taken is the same as any other one. (as for the walker example)
- random() produces a uniform distribution.

---

### Probability and Nonuniform Distributions
The main objective is to produce nonuniform distribution of random numbers, where some outcomes are more likely than others. \
<u>Probability of the fittest:</u> **Darwininian natural selection.** \
<br>
Nonuniform distributions with random():
- fill an array with numbers, some of them are the same
```
    let stuff = [1, 1, 2, 3, 3];
    let value = random(stuff);
```
- allow an event to occur if a random number is within a certain range
```
    let probability = 0.1;
    let r = random(1); // random float between 0 and 1
    if (r < probability){
        event();
    }
```
This method can also be used to distribuite unequal probabilities, by checking the differente ranges between 0 and 1.
- control probabilities of events occuring sporadically (i.e. every x frames)