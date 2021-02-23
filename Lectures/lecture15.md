# lectureFifteen

### Other interestingness Measure: Interest

* Interest (correlation/lift) = P(A ^ B) / P(A)P(B)
* If A and B are negatively correlated, the value is less than 1; else they are positively correlated.
* If two items are not positively correlated, we must not consider those items even if confidence is more.
* Strong rules are the rules that passes support criteria and has confidence == 100%

### Improve Apriori Efficiency

* Hash-based bucket itemset counting: A k-itemset whole corresponding bucket count is below the threshold cannot be frequent.
* Transaction reduction: A transaction that doesnt contain any frequent k-itemset is useless in subsequent scans.
* Partitioning: Any itemset that is potentially frequent in DB must be frequent in at least one of the partitions of DB.
* Sampling: Mining on a subset of a given Data, lower support threshold + a method to determine completeness.
* Dynamic Itemset counting
