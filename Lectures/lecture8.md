# lectureEight

* __Data Cleaning__

  * Fill missing values
    1. Ignore Tuple
    2. Fill missing value manually
    3. Fill missing value automatically
    4. Use a global constant to fill missing value
    
  * Identify outliers and smooth out noisy data
    1. Binning Method - Used when the data is not exact/absolute and variation is seen in the data. So        we need to smoothen the data.
    2. Clustering - Scatterplot visualization and identify outliers and smooth out data.
    
  * Correct inconsistent data
    1. Here the data means the same but the value is different. Eg. Gujarat == Gujrat but both strings arent same. So that should be removed.
  
  * Resolve Redundancy by Data Integration
    1. Multiple sources have exact same data. When integrating/scrapping data into one, that redundancy must be removed.
    

### Fill Missing Values

* __Ignore the tuple (record/row)__:
  - Usually done only when __class label__ is missing.
  - Eg. task is to distinguish between "Spam" and "Not Spam"; it class lable is missing then it must be discarded.

* __Fill missing value manually__:
  - Use mean to filling missing value. Also can use attribute mean for all samples belonging to same class. 
  - Fill missing values automatically.
    a. By making use of learning algoirthm such as Naive Bayes, Decision tree etc.
* Use a global constant to fill the missing value such as NaN, Unknown

### Identify outliers and smooth out noisy data

* __Binning method__:
  - Data Binning or Bucketing is a data preprocessing technique used to reduce effects of minor observation errors.
  - Here we divide into different class ranges; based on the range of the data and data density.
  - We must find minimum and maximum value for the range.
  - The original data values that fall in a given small interval called as a bin are replaced with a value that represents a small interval called the central interval.
  
  * Steps of Binning Method:
    Data: 4,8,9,15,21,21,24,25,26,28,29,34
    1. Partition into equal depth. Here n=4; 
       So, Bin 1: 4,8,9,15
           Bin 2: 21,21,24,25
           Bin 3: 26,28,29,34
    2. Smooth by bin means. (Data value must be sorted) OR Smoothing by bin boundaries.
    
  * It is a __top down splitting technique__ based on specified number of bins.
  * It is also used as __discretization method__ and __concept of hierarchy generation__.
  * For example, attribute values can be discretized by applying equal width or equal frequency binning and then replacing each value by bin mean or median.
  * It can be applied recursively to resulting partitions to generate concept hierarchies.
  * It doesnt use class information; and therefor it is __unsupervised discretization technique__.
    
* __Clustering__:
  * Clustering is a process of partitioning a set of data into a set of meaningful sub-classes called clusters.
  * Enables abstraction of large amounts of data by forming meaningful groups or category.
  
  
### Correct Inconsistent Data:

 * It contains similarity in codes or names.
 * We can use stemming etc. to check for grammar, names etc.
 
### Resolve Data Redundancy:
 * Database normalization prevents reduncdancy.
 * Also appropriate use of foreign keys can help to reduce it.
    
    
