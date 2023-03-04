# Casual inference

This is a learning exercise based on the book Causal Inference in Statistics.

## TODOs

- dockerize
- jupyter
- SQL: postgres or snowflake
- pandas
- dowhy.py
- chap 1 study questions
- ChatGPT and causal DAG and experiments

## backlog TODOs

- mediator DAG ... "Healthy Diet" --> Blood Glucose --> Artery Damage

## Bayes examples -- short cut information ...less to traverse before we get a
hit

- concentration ratios
- do paintings
- hawks flys over smaller partitions of total area where concentration is higher
- its more likely to find mushrooms in burned woods because there is a higher
  concentration of mushrooms in burned woods compared to burned woods area in
  the total area

# References

- Judeo Pearl's *Book of Why?*
- workbook on Causal Inference

# Backlog of diagrams to make

- DAG of heart attack factors - 2 groups are genetically insulin resistant but 1 group has much lower A1C ...why?
- DAG of ZKML catalyst to start the chain reaction
- DAG Heart Attack of insulin resistant vegans

# Musings

- acyclical DAG and econ IO model
- acyclical DAG and spatial W matric in a spatial regression
- Geo-political institional factors as RCE (randomized control experiment, Pima Indians, Schools, Federated places)

# Dissertation's Spatial inequality is another version of Simpson's Paradox 

- both are aggregation problem where we looses information by aggregating across the key partitioning 
- because the causal relationship happens within the partitioning


# Bayes

ChatGPT geometric proof

```
Let A and B be two events such that P(A) > 0 and P(B) > 0.

Then, the probability of A given B is:

P(A | B) = P(A ∩ B) / P(B)

Now, let's draw a Venn diagram to illustrate this.

Let A and B be two circles, with A being the larger circle. The intersection of A and B is the area of overlap between the two circles.

Now, the probability of A given B is equal to the area of overlap divided by the area of B.

Therefore, P(A | B) = P(A ∩ B) / P(B).
```
