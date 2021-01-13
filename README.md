# IT trends
Brief IT trends analysis, including educational levels of people working in the field, salary changes and programming languages popularity.
The analysis is based on StackOverflow surveys of the years 2014-2020.


### List of files
* IT_trends.ipyb - The source code.
* developer_survey_2014.zip - StackOverflow survey results from the year 2014.
* developer_survey_2015.zip - StackOverflow survey results from the year 2015.
* developer_survey_2016.zip - StackOverflow survey results from the year 2016.
* developer_survey_2017.zip - StackOverflow survey results from the year 2017.
* developer_survey_2018.zip - StackOverflow survey results from the year 2018.
* developer_survey_2019.zip - StackOverflow survey results from the year 2019.
* developer_survey_2020.zip - StackOverflow survey results from the year 2020.

### How to use
Download all the datasets, unzip them, then download _IT_trends.ipyb_, open it in jupyter notebook and run.

### 3rd party libraries
The project uses pandas, numpy, matplotlib and seaborn.

### Useful functions
Following functions are implemented in the file:
* `separate_items()` - if the entries of a series are strings which contain a number of values separated by a certain token,
this function transforms the entries into lists of these values.
* `count_values()` - returns a count of unique values, when entries of a series are lists of values.
* `assemble_list_of_technologies()` - when given a list of dataframe columns - performs two previous functions and assemble the results into one series.

### License
This code is under APACHE LICENSE 2.0

### Author & Acknowledgements
Author: Zeev Peisakhovitch
All the data were taken from: (https://insights.stackoverflow.com/survey)
