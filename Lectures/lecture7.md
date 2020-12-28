# lectureSeven

### Case Study: Spending Score Data

* It has Customer ID, Genre (Male, Female), Age (Numerical), Annual Income (Dollars) and output Spending Score value.

* Thorough case study is required to understand the relation between data. We need to develop a model (algorithm) for prediction of unknown set of values in the dataset.

* Fill the missing values by proper filling technique. If age parameter of female is missing, then we can take mean of all the female age and replace; instead of all set of values.

* The target attribute is called __Class Label__. Never fill the missing values in the Spending Score, and replace them instead.

* __BONUS__: Amazon initially sold books only. They took manual reviews and ratings from the readers and they recommended to the customer. Today, they have automated the process. Also, Netflix also follows the similar concept of recommendation.

* When we are analyzing the data, we can first plot a scatterplot. It shows how concentrated or how the data is scattered; and in this way we can know if there is any outlier.

* For Dataset understanding- Mean, mode, median, min, max, SD, Variance, Correlation. Then Visualize with scatterplot by multiple labels.

* Range of Correlation: -1 to 1

* Here Correlation ~ 0 (i.e. -0.01 here)

* NO CORRELATION between the attributes and so cant remove.

* If Correlation near to 1 or -1, so both records are duplicated and both actually represent the same. Thus we must remove redundant attributes.

* By this, we can improve the final execution/comutational time by Data Reduction Technique.









