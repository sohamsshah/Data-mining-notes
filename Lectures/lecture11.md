# lectureEleven

## Association Rule Mining

Given a set of transactions, we need rules that will predict the occurence of an item based on occurences of other items in the transaction.

* Market-Basket Transactions

There are transactions given in form of data that how customers purchased items. `TID` and `Items` are two columns available. 

* Itemset: Collection of one or more items
* k-temset: Set that contains k items
* Support Count: Frequency of occurence of an itemset
* Support: Fraction of transactions that contain an itemset Eg. {{Milk, Bread,Chocolate}} = 2/5

* Frequent Itemset: An itemset whose support is greater than or equal to minimum support threshold.

* Confidence: Out of the total transactions have input set, which has the Output of the transaction.

Eg. {Milk, Chocolate} => Pepsi

Support s = Sigma(Milk, Chocolate, Pepsi) / Total = 2/5 = 0.4

Confidence = {Milk, Chocolate}/{Milk, Choclate, Pepsi} = 2/3 = 0.67





