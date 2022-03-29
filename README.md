# This is Jeopardy Project

### Codecademy's Data manipulation with Pandas project

Instructions:

* Write a function that filters the dataset for questions that contains all of the words in a list of words. 
For example, when the list ["King", "England"] was passed to our function, the function returned a DataFrame of 152 rows. 
Every row had the strings "King" and "England" somewhere in its " Question".
Note that in this example, we found 152 rows by filtering the entire dataset. 
You can download the entire dataset at the start or end of this project. The dataset used on Codecademy is only a fraction of the dataset so you won’t find as many rows.
Test your function by printing out the column containing the question of each row of the dataset.

* We may want to eventually compute aggregate statistics, like .mean() on the " Value" column. But right now, the values in that column are strings. 
Convert the " Value" column to floats. If you’d like to, you can create a new column with the float values.
Now that you can filter the dataset of question, use your new column that contains the float values of each question to find the “difficulty” of certain topics. 
For example, what is the average value of questions that contain the word "King"?
Make sure to use the dataset that contains the float values as the dataset you use in your filtering function.

* Write a function that returns the count of the unique answers to all of the questions in a dataset. 
For example, after filtering the entire dataset to only questions containing the word "King", we could then find all of the unique answers to those questions. 
The answer “Henry VIII” appeared 3 times and was the most common answer.

* Explore from here! This is an incredibly rich dataset, and there are so many interesting things to discover. 
There are a few columns that we haven’t even started looking at yet. Here are some ideas on ways to continue working with this data:
  * Investigate the ways in which questions change over time by filtering by the date. How many questions from the 90s use the word "Computer" compared to questions from the 2000s?
  * Build a system to quiz yourself. Grab random questions, and use the input function to get a response from the user. 
  Check to see if that response was right or wrong. Note that you can’t do this on the Codecademy platform — to do this, download the data, and write and run the code on your own computer!
