# lectureTen

### Z-score (Gaussian Distribution):

* It transforms data in such a way that the mean value = 0. Means that the sum of values on left side and sum of values right side are equal. The SD is 1.

* It is a normalization technique

* Given distribution of data, each value will have sample mean value subtracted and then divided by SD of while dataset.

* Formula: ( x_i - mean(x) )/ stdev(x)

* In contrary to minmax transformation, it doesnt guarantee that all dataset attributes will be in same scale. While in minmax, all attributes are in same range.

* While, the Gaussian Distribution solves the problem of outliers.

* Refer: [Covid19 Dataset](https://www.covid19india.org/) for Data Analysis.

* The Gaussian Distribution is Bell Shaped Curve; which is widely seen in the Nature. Eg. the Covid 19 is Bell Shaped curve.

* Bell Shaped curve have a peak value that signifies the time where covid was highest and then the cases started decreasing.

### Decimal Scaling:

* In this technique we mive decimal point of values in attribute.

* This depends on the max value of the attribute

### Discretization:

* Discretization techniques can be categorized based on how the seperation is performed, such as whether it uses class information or which direction it proceeds. (Top down or Bottom up)

* Raw values of numeric attribute(eg. age) which are replaced with interval labels(0-10, 11-20..etc.) or conceptual labels(eg. youth, adult etc.)

### Concept hierarchy generation for nominal data:

* Attributes such as address can be generalized to high level concepts like city, country etc.

### Data Reduction

* Reducing number of attributes
  - Data cube aggregation: applying roll up, slice or dice operations
  - Removing irrelavant attribute: Attribute selection, searching the attribute space

* Reducing number of attribute values:
  - Binning: Reducting number of values by grouping them in intervals
  - Clustering
  - Aggregation and Generalization

* Reducing number of tuples
  - Sampling: Only sample data are used for mining purpose. (Used in Exit Polls. Only 10000 people are asked whom they voted, but based on just that the exit poll is predicted)


