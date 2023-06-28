# Fine-Food-Reviews

Data Source: https://www.kaggle.com/snap/amazon-fine-food-reviews

Context
This dataset consists of reviews of fine foods from Amazon. The data span a period of more than ten years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.

Data includes:

Reviews from Oct 1999 - Oct 2012
568,454 reviews
256,059 users
74,258 products
260 users with > 50 reviews

Attribute Information: Number of Attributes/Columns in data: 10

Id
ProductId - unique identifier for the product
UserId - unique identifier for the user
ProfileName
HelpfulnessNumerator - number of users who found the review helpful
HelpfulnessDenominator - number of users who indicated whether they found the review helpful or not
Score - a rating between 1 and 5
Time - timestamp for the review
Summary - brief summary of the review
Text - text of the review

Goal:

Given a review, determine whether the review is positive (Rating of 4 or 5) or negative (rating of 1, 2, 3)
