# Feature Engineering and Data Preprocessing

Final project of the Machine Learning course at Shahid Beheshti University in Tehran!

Course Instructor: [Zhinoos Adibi](https://github.com/zhinoos-adibi)

#### Project objectives:
- Identifying outlier data in the dataset using the boxplot method
- Identifying missing data and managing them

One of the data cleaning steps is identifying outlier and missing data and managing them in the dataset, as the presence of outlier and missing data in the dataset can cause problems in the learning process of machine learning models.

#### Project steps:
1. Creating a dataframe of 150 random numbers with three columns: age, height, weight. The random numbers are generated using the numpy library, and the mean, standard deviation, and number of data corresponding to each column are considered as follows, with a random.seed of 124:
- age column:
Mean: 60, standard deviation: 14, number of data: 150
- height column:
Mean: 175, standard deviation: 20, number of data: 150
- weight column:
Mean: 90, standard deviation: 13, number of data: 150

2. Assigning 5 missing data to 5 cells of the table.

3. Identifying the assigned missing data and replacing them with the mode of the corresponding column.

4. Detecting outlier data in the age column using the boxplot method, and removing the corresponding row with outlier age data from the dataframe.
