# lectureFive

### DATA PREPROCESSING

#### Outline of this Unit:

* Mean, mode, median, range
* Attribute Type
* Data Cleaning
* Data Integration
* Data Transformation
* Data Reduction
* Encoding

#### Why to pre-process Data?
* Real world data is *dirty*
  1. Incomplete: missing values, lack of certain attributes of interest, only aggregate data
  2. Noisy Data: Contains errors and outliers.
  3. Inconsistent: Containing similarity in codes or names (grammar mistakes like "Gujarat" and "Gujrat" are same but treated differently by our code)
 
 * Garbage In Garbage Out (GIGO) is apt here. Data must be of good quality for quality results.
 
 * Duplicate or Missing Data may cause incorrect or even misleading statistics.
 
 * Data preparation, cleaning, transformation are majority task (90%) in Data Mining.
 
 * Data Preprocessing prepares raw data for further preprocessing.
 
 #### MEAN
 * Mean is arithmetic average of the dataset.
 * Mean = (sum(avg))/n
 
 #### MEDIAN
 * Middle value of the dataset
 * Arrange in Sorted form
 * If odd, n/2th observation
 * If even, (n/2th + n+1/2th)/2
 
 * If there is large difference between Mean and Median, there can be outlier.
 * But, if there is less difference, still there can be an outlier; because reange can be different.
 
 #### MODE
 * The number that occurs most often within a set of numbers.
 * Mode is used for maximum occuring value in a dataset.
 
 #### RANGE
 * Range = max - min
 
 #### STANDARD DEVIATION
 * How each value differs from Mean Value
 * Measure of how much data is spread
 * STD_DEV = sqrt(1/n-1 (for x in range(n): (x-mean)^2))
 * Variance = (STD_DEV)^2
 * Average deviation of every value from mean is STD_DEV
 * Good way to check for outlier
 
