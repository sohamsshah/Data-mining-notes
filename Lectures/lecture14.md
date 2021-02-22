# lectureFourteen

### Core of Apriori Algorithm

* Use frequent k-1 itemsets to generate candidate frequent k-itemsets
* Use DB scan and pattern matching to collect counts for the itemsets

### Bottleneck of Apriori Algorithm: Candidate Generation
* Huge candidate sets: 10^4 frequent 1-itemset will generate 10^7 candidate 2-itemsets
* To discover a frequent pattern of size 100, one needs 2^100 candidates!
* Multiple DB scans: Needs (n+1) scans for n-longest pattern


