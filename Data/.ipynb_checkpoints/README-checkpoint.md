# Audiobooks Purchase Dataset

You are given data from an audiobook app. Logically, it relates to the audio version of books only. Each customer in the database has made a purchase at least once. We want to create a machine learning algorithm based on our data that can predict if a customer will buy again from the audiobook company. In this dataset each row represents a person.

The sample dataset is taken from the *Section 51: Deep Learning - Business Case Example* of *The Data Science Course 2023: Complete Data Science Bootcamp* on [Udemy](https://www.udemy.com/course/the-data-science-course-complete-data-science-bootcamp/). The dataset has 12 columns features to be used predicting the label which is Targets columns in the dataset. The .csv file does not contain any column names. You can add the names of the columns as follows starting from the first column.

## Data Dictionary

- ID: Customer ID
- Book length (mins)_overall: Sum of the lengths of all purchases. In minutes.
- Book length (mins)_avg: The sum divided by the number of purchases. In minutes.
- Price_overall: Sum of all paid price for all purchases. In US Dollars.
- Price_avg: Price_overall devided by the number of purchases. In US Dollars.
- Review: It shows if the customer left a review.
- Review 10/10: It measures the review of a customer on a scale from 1 to 10. The black review scores is filled with the average of the review score which is 8.91.
- Minutes listened: Total minutes listened
- Completion: Completion is the total minutes listened divided by the total length of books a person has purchased.
- Support Requests: Total number of support requests a person has opened.
- Last visited minus Purchase date: Measuring the difference between the last time a person interacted with the platform and their first purchase date.
- Targets: It is 1 if a person returned and 0 if he or she didn't.



