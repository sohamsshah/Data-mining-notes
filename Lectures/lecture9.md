# lectureNine

### Data Transformation Techniques

1. Smoothing
2. Attribute construction
3. Aggregation
4. Normalization
5. Discretization
6. Concept Hierarchy

* __Smoothing__:
  - It works to remove noise from data
  - Correcting data inconsistencies
  - Eg. binning, regression, clustering
  
* __Attribute Construction__:
  - It is referred as new attributes are constructed and added from the given set of attributes to help the mining process.
  - Eg. adding quaterly income to form yearly income attribute
 
* __Aggregation__:
  - Add a new attribute to the dataset

* __Normalization__:
  - It is a scaling/standardization/mapping technique.
  - New range from existing range
  - Three techniques:
    1. Min-Max Normalization: We fit the data in a defined boundary, or a predifined interval eg. [0,1]
    2. Gaussian Normalization(Z-Score): It will transform data such that the distribution will have mean value 0 and standard deviation 1.
    3. Decimal Scaling: In this we move decimal point of values of the attribute.
    
* __Min-Max Normalization__:
  - Min: 16, Max:40
  - V1 = 16, V2 = 20, V3=30, V4=40
  - NewMax = 1
  - NewMin = 0
  
  - Formula: V_new = ((v - MinA)/(MaxA-MinA)(NewMax - NewMinA)) + NewMinA
  
  - For V1=16,
    
    MinMax(V_new) = (16-16)/(40-16)X(1-0) + 0
    V_New = 0
    
  - For V2, MinMax = 0.16
  - For V3, MinMax = 0.58
  - For V4, MinMax = 1
  
  - Drawbacks: If there are outliers, the Normalized Data will be having most values towards zero as Maximum will be too high(as outlier). So, better approach is needed. 


  
    
  


