# lectureFour

### Data Mining Architecture:

Architecture paradigms:
1. Collect data from: Database, Data Warehouse, WWW, etc.
2. Cleaning the dataset
3. Integrate and select the features
4. Database and Data Warehouse Server
5. Data Mining Engine (set of algorithms and models)
6. Knowledge Base (manual user inputs regarding the application)
7. Pattern Evaluation
8. Graphical User Interface

Data Mining Engine:
1. Characterization
2. Association
3. Correlation
4. Classification
5. Outlier Analysis

Pattern Evaluation Module:

Employs interestingness measures and interacts with the data mining modules so it focuses into search towards interesting patterns.

* Dense Data: The data points which are nearer to each other in a Dataset.
* Sparse Data: The data points are comparatively far from each other in a Da*taset.

Knowledge base:

* Domain knowledge that is used to guide the search or evaluate the interestingness of patterns.

* It can include concept hierarchies that are used to organize attributes or attribute values into different levels of abstraction.

* Eg. user beliefs etc.

### KDD (Knowledge Discovery in Databases):
Process:
1. Selection of target data (Data relavent to the analysis task are retrieved from DB)
2. Preprocessing 
  i. Data Cleaning- Remove noise and inconsistent Data
  ii. Data Integration - Where multiple data sources may be combined
3. Transformation (approximate for mining by performing aggregation operations) As an example - To make it in same range - Normalize the Data.
4. Data Mining: Apply intelligent methods and algorithms to extract data patterns.
5. Visualization and Knowledge Representation by various techniques.

### Issues with Data Mining:

1. Mining Methodology
  * New kinds of methods: Based on Domain requirement on same database in different ways and require the development of numerous data mining techniques
  * Multidimensional Data space: Complex dataset and large volume
  * Interdisciplinary Effort: Requires wide knowledge of various disciplines which is required
2. User Interraction
  * Interactive Mining: Flexible user interface and make an exploratory mining environment
  * Incorporation of Background Knowledge: External domain knowledge, constraints, rules and              information should be incorporated.
  * Presentation and visualization of data mining results: Must be human-friendly and vivid and flexible
3. Efficiency and Scalability
  * Algorithm: Efficient and scalable in order to extract from huge data. It should be fast, running time and acceptable by applications.
  * Parallel, distributed and incremental mining algorithms: Computational complexity issues and wide distribution of data
    
4. Diversity of Database types 
  * Handling complex types of data: Streams, time series,graph, social network and multirelational data.
  * Mining dynamic, networked and global data repositories: Discovery of knowledge from structured, unstructured and semi-structured data. Web mining, multisource data mining, information network mining
  
5. Data Mining on Society
  * Privacy-preserving data mining
  * Cyber attacks
  * Social Impacts
  * Invisible Data Mining (the users are unaware of this data collection)



