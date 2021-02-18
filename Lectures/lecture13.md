# lectureThriteen

Equation to calculate confidence: Number of Transactions (total) / Number of Transactions of LHS

A ^ B -> C

Person who buys A and B, probability of C being bought together.

A -> B ^ C

Person who buys A, probablity of B and C being bought together.

It is better to calculate association rule to have n-1 itemset from given frequent items on Left side, and 1 on right side.

#### Apriori Algorithm

* Decide a constant support value, `minimum_support_count` = 2
* Then find support relating to each Transaction ID and if support < `minimum_support_count` remove them and go to next iteration.
* Then continue by abiding by Apriori Property.
* STOP when we get optimal frequent itemset.

If `minimum_support_count` is less, Time required to calculate the frequent pattern is more and vice versa.

* Interestingness Measurements *

Objective Measures:
Two measures 
i. support
ii. confidence

Subjective Measures:
A rule is interesting if
i. It is unexpected or surpising to the user
ii. Actionable (user can do something about it) -> Must be logical and proper values of support count and confidence.








