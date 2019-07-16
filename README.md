### Date created
July 16th 2019

### Project Title
Exploring US Bikeshare Data

### Description
In this project, I had to make use of Python to explore data related to bike share systems for three major cities in the United
States — Chicago, New York City, and Washington. I had to write code to (a) import the data and answer interesting
questions about it by computing descriptive statistics, and (b) write a script that takes in raw input to create an interactive
experience in the terminal to present these statistics.

### What Software Do I Need?
To complete this project, the following software requirements apply:

- You should have Python 3, NumPy, and pandas installed using Anaconda
- A text editor, like Sublime or Atom.
- A terminal application (Terminal on Mac and Linux or Cygwin on Windows).

### The Datasets
Randomly selected data for the first six months of 2017 are provided for all three cities. All three of the data files contain the same core six (6) columns:

- Start Time (e.g., 2017-01-01 00:07:57)
- End Time (e.g., 2017-01-01 00:20:53)
- Trip Duration (in seconds - e.g., 776)
- Start Station (e.g., Broadway & Barry Ave)
- End Station (e.g., Sedgwick St & North Ave)
- User Type (Subscriber or Customer)

The Chicago and New York City files also have the following two columns:
- Gender
- Birth Year

### Statistics Computed
You will learn about bike share use in Chicago, New York City, and Washington by computing a variety of descriptive statistics. In this project, you'll write code to provide the following information:

#1 Popular times of travel (i.e., occurs most often in the start time)

- most common month
- most common day of week
- most common hour of day

#2 Popular stations and trip

- most common start station
- most common end station
- most common trip from start to end (i.e., most frequent combination of start station and end station)

#3 Trip duration

- total travel time
- average travel time

#4 User info

- counts of each user type
- counts of each gender (only available for NYC and Chicago)
- earliest, most recent, most common year of birth (only available for NYC and Chicago)

### Files used
- washington.csv

- new_york_city.csv

- chicago.csv

### Credits
- https://pandas.pydata.org/pandas-docs/stable/generated/pandas.Series.dt.html

- https://stackoverflow.com/questions/775049/how-to-convert-seconds-to-hours-minutes-and-seconds
