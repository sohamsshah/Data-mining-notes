# lecture 19

### Advantages of Decision Tree
- Inexpensive to construct
- Extremely fast at classifying unknown records
- Easy to interpret for small sized trees
- Accuracy is comparable to other techniques

### Key Requirements for Classification

* **Sufficient Data**: Enough training cases must be provided
* **Attribute Value Description**: Expressible in terms of params
* **Discrete Values of target Value** The Target class must be either boolean or multiclass discrete.

### Important terms for Decision Tree
* Entropy
* Information gain
* Gini Index

### Entropy (E)
* It defines the certainity of a decision (If value is 1, it is completely certain. If 0, it is completely uncertain)
* The value is between 0 to 1  as it is a probability based measure to calculate the amount of uncertainity.
* ![image](https://user-images.githubusercontent.com/47717492/110273137-e6be2900-7ff1-11eb-97ac-5e3bf467244e.png)
* It measures how much information we dont know.
* How much information we can gain
* **Which attribute is the best?**
  * The attribute with largest expected reduction in entropy is the best attribute the use next
  * Because if we have large expected reduction it means we take away that attribute has a big eddect, meaning it must be very certain.
  * Measuring Homogeneity of a node: Maximum when records are equally distributed.
* It is built top down from a root node and partitions the data into subsets that contains instances with similar values.
* ID3 algo uses entropy to calculate the homogeneity of a sample.
* If sample is homogogenous then entropy = 0 and when it is perfectly divided, entropy = 1.

### Information Gain (I)
* Information gain can be used for continuous valued attributes.
* Attributes that has highest information gain is selected for split.
* Eg. if we have two classes P and N.
* We have S samples, out of which p belong to class P and n belong to class N.
* Information gain can be calculated as:
* ![image](https://user-images.githubusercontent.com/47717492/110274215-503f3700-7ff4-11eb-989b-88dd3a4413b8.png)


