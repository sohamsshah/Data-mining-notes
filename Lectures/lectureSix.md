# lectureSix

### STANDARD DEVIATION EXAMPLE

* The owner of Indian restaurant is interested in how much people spend at restaurant.

* He examines 10 randomly selected receipts for parties and writes down number of minutes spent at the restuarant:

* He gets SD:17 and Mean:49.2.

* Now, 49.2-17 = 32 and 49.2 + 17 = 66.2

* SD can be thought of measuring how far the data values lie from mean.

* They can improve the average time spent at restaurant by fast service etc ways if he has the data.

* If all data are same, the variance and SD are zero.


### ATTRIBUTE TYPES:

* An attribute is a property of the object.

* It also represents different features of object.

* Attribute types are into 4 categories:
  1. Nominal Attribute: They are named attributes which can be seperated into discrete values. Eg. name, color etc.
  2. Ordinal Attribute: They are order of values, thats important and significant, but difference between each one is not really known. Eg. Rating, Rank etc. We cant quantify it.
  3. Interval Attribute: It comes in form of numerical value where difference between points is meaningful. Eg. Temperature: 10-20, 30-40 etc. It doesnot have true zero.
  4. Ratio: It looks like interval attribute, but it has true value. Eg. weight. It has absolute zero.
  
### DATA PREPROCESSING TASKS

Data Cleaning -> Data Integration -> Data Reduction -> Data Transformation


### FILLING MISSING VALUES:

* Never ever delete the data.
* Can Fill it with Mean
* Can Fill it with Median
* Can Fill it with Mode

But filling strategy must be decided based on Dataset.

### EXAMPLE: 

For example if there is Dataset having Salary and Age params. If we fill with Mean or Median values, the age=30 and age=60 will get same value. Which is logically incorrect to put.

So, other technique for instance that can be used is: Put data in range form.

Eg. if there is missing value for salary at age=30 and age=60. We can convert data in range. For example, consider average of all salary values in age range 10-20, 20-30, 30-40 and so on. So, even there is missing value in the range for salary, we are taking average only so it gets compensated. In this way we can have unique and filled values for all age groups in the dataset.

