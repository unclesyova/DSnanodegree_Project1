# It trends
Brief IT trends analysis based on StackOverflow surveys of years 2014-2020.


### How to use
Just download _IT_trends.ipyb_ open it in jupyter notebook and run.

### 3rd party libraries
The project uses pandas, numpy, matplotlib, seaborn.

### Useful functions
Following functions are implemented in the file:
* `separate_items()` - if entries of a series are strings which contain a number of values separated by a certain token,
this function transform the entries into lists of these values.
* `count_values()` - returns a count of unique values, when enties of a series are lists of values.
* `assemble_list_of_technologies()` - given a list of dataframe columns performs two previous functions and assemble the results into one series.

### License
This code is under APACHE LICENSE 2.0

### Author
Zeev Peisakhovitch
