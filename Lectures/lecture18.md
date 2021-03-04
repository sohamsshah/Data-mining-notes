# lectureEighteen

### Introduction to classification

- Classification is **Supervised Learning Method**.
- It is a data mining function that assigns items in a collection to target categories or classes.
- Goal of classification is to accurately predict the target class for each case in the data.
- For example, classification model could be used to identify loan applicants as low, medium or high credit risks.
- Suppose a Database D is given as D = {t1,t2, t3..,tn} and set of desired classes C = {C1,C2,...,Cn}
- Classification problem is to define the mapping m in such a way that which tuple of database D belongs to which class of C.
- We divide D into equivalence classes.

### Classification: Definition

- Given a collection of records (training set)
  * Each record contains a set of attributes, one of them is class.
- Find a model for class Attribute as a function of the values of other attributes.
- Goal: prevously unseen records should be assigned a class as accurately as possible
  * Test set is used for this.



### Illustrating Classification Task
![image](https://user-images.githubusercontent.com/47717492/109913407-ebbe6800-7cd3-11eb-8241-ec3e8cd1f99c.png)
- Learning Algo: It is classifier such as Naive bayes etc.
- In Induction Step, the training set is being trained using the Learning Algorithm and Model is trained.
- Model is applied and tested on Test Set.

### Classification Example
* Predicting tumor cells as benign or malignant
* Classifiying credit card transactions as legitimate or fraudulent
* Classifiying secondary structures of protein as alpha-beta etc.
* Categorizing news stories as finance, weather, entertainment, sports etc.
* Identify individuals with credit risks (high, low, medium, unknown etc. multiclass)

