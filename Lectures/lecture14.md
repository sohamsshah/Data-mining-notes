# lectureFourteen

### Core of Apriori Algorithm

* Use frequent k-1 itemsets to generate candidate frequent k-itemsets
* Use DB scan and pattern matching to collect counts for the itemsets

### Bottleneck of Apriori Algorithm: Candidate Generation
* Huge candidate sets: 10^4 frequent 1-itemset will generate 10^7 candidate 2-itemsets
* To discover a frequent pattern of size 100, one needs 2^100 candidates!
* Multiple DB scans: Needs (n+1) scans for n-longest pattern

### Criticism to Support and Confidence

Example:
* Among 5000 Students, 3000 Play Basketball, 3750 eat cereal, 2000 play basketball and eat cereal

Rule: {basketball} => {eat cereal}

Support: Number of students who eat basketball and eat cereal/Total Students = 40%
Confidence: Number of students who basketball and eat cereal/Total Students play basketball = 66.7%

But out of total(5000), 3750 students eat cereal i.e. 75% - which is higher than 66.7% which is misleadng.

### Incremental Mining of Association Rules
* With increasing use of record-based DBs whose data is being continuously added, updated, deleted etc.
* Eg. Web log, stock market, grocery sales data, e-commerce, daily weather records etc.
* (Data -> Mining -> Business Strategy -> Data ->)
* Need to re-run mining algorithm on updated Database everytime.

