## Data Wrangling with JSON

Exercises for Springboard's Data Science Career Track bootcamp

### The goals of the exercises:

+ To get familiar with json package and json_normalize function from Pandas
+ To practice extracting JSON into a Pandas dataframe
+ To extract and analyze data from the dataset of the projects funded by the World Bank (source: http://jsonstudio.com/resources/)

### Exercises:

Using data in file 'data/world_bank_projects.json',

+ Find the 10 countries with most projects
+ Find the top 10 major project themes (using column 'mjtheme_namecode')
+ In 2. above you will notice that some entries have only the code and the name is missing. Create a dataframe with the missing names filled in

***

### Steps of the process

+ Load JSON into a data frame, using Pandas' read_json function or json.load() method
+ Use json_normalize() function for columns with nested data
+ Find the top countries by using value_counts() method
+ Fill missing values by using np.nan and fillna() method with back-propagation 
