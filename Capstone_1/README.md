## Capstone Project 1 - Subscription for Bank Deposits

### Dataset

The data for this project are sourced from the UCI Machine Learning repository and represents the results of direct marketing campaigns (phone calls) of a Portuguese banking institution. The data set has 45,211 instances and 20 features (input variables), stored in a .csv file.
http://archive.ics.uci.edu/ml/datasets/Bank+Marketing.

**Number of Instances**: 41188
**Number of Attributes**: 21 output attribute

### Exploratory Analysis

**1. Loading required libraries and the dataset.**

**2. Looking at overall characteristics of the dataset:**
  * Dataset shape
  * Number and types of variables
  * Overall distributions of the numerical and categorical variables and their analysis
  * Levels of categorical variables as percentage of the overall number of instances

No outliers detected.

### Data Cleaning and Feature Engineering

**1. Removing duplicates and 'unknown' levels of categorical variables.**

**2. Combining sparse categories:**
  * Variable 'job': Combining entrepreneurs and self-employed into self-employed
  * Variable 'job': Combining administrative and management jobs into admin_management
  * Variable 'job': Combining blue-collar and tecnician jobs into blue-collar
  * Variable 'job': Combining retired and unemployed into no_active_income
  * Variable 'job': Combining services and housemaid into services
  * Variable 'marital': Combining single and divorced into single
  * Variable 'education': Combining basic school degrees

**3. Comparing variables 'poutcome' and 'pdays' and solving for mislabeled 'pdays' rows**
