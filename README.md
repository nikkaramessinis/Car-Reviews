# Car-Reviews
Assignment 2: Modelling and Prediction Applications of Artificial Intelligence
This assignment is worth 50% of your total grade.
Assessment Criteria for Part One (6 marks)
Your solutions to part one will be assessed according to the following criteria.
A mark will be awarded for each of the following criteria that are satisfied. Marks will not be
awarded for a particular criterion if there are errors identified in the code for that particular
aspect of the software.
Assessment criteria for part one Marks
awarded
Does the submission demonstrate that words and punctuation, which are unlikely to
affect sentiment, have been excluded from the sentiment classifier AND that the
remaining words are not being handled in a case sensitive way?
1
Does the submission demonstrate that words with the same stem have been
appropriately recognised and treated as variations of the stem? This should be
demonstrated for at least 3 different stems.
1
Does the code produce some output to demonstrate that a vector has been created
for each review, where each element in the vector represents EITHER a binary
variable indicating the presence of a word/stem in a review OR the number of times
that a word (or word stem) appears? Note that the output does not need to show
the vector for all reviews, this only needs to contain a small sample of reviews.
1
Does the code clearly show that an appropriate Naïve Bayes model has been used
for classification, either through the use of an existing library or coded from scratch.
1
Does the code clearly show that 80% of the data has been used to train the
classification model, and that the remaining 20% of the data set has been used as
test data? AND does it show that only the training data has been used up to the
point where the model has been trained (no test data)? AND is the code able to
cope with words that appear in the test data but not in the training dataset?
1
Does the code output a confusion matrix demonstrating the performance of the
Naïve Bayes classifier? The confusion matrix must clearly indicate the proportion of
True Negatives, False Positives, False Negatives and True Positives.
1
Assessment Criteria for Part Two (4 marks)
Your solutions will be assessed according to the following criteria:
Assessment criteria for part two Marks
awarded
Does the Jupyter notebook include a markdown/comment section that
clearly explains how the approach taken in part two is expected to
improve on the solution to part one. Are the reasons for the expected
improvements clearly justified and explained with one or more references
(e.g. to a published source scientific paper, article, book)?
1
Does the submission clearly explain the steps that have been taken to
implement the improved approach? These should be written in a way that
one of your peers who may not have researched the same approach could
1
Assignment 2: Modelling and Prediction Applications of Artificial Intelligence
understand. This may consist of code comments, Jupyter markdown, or a
mix of both.
Does the code implement the described approach appropriately? (i.e.
does the code actually do what is described?)
1
Does the code output a new classification matrix for the “improved” part
two approach AND Is there markdown or comment that clearly discusses
and compares the performance of the part one and part two classification
approaches and explains whether or not the expected improvements were
achieved (and why this may be the case).
1
