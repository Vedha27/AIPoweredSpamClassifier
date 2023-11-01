# AI-PoweredSpamClassifie
In the case of spam detection, a trained machine learning model must be able to determine whether the sequence of words found in an email is closer to those found in spam emails or safe ones.
System Requirements: –

Hardware

OS – Windows 7, 8, and 10 (32 and 64 bit)
RAM – 4GB
Software:

Python
Anaconda navigator
Python built-in module

1.Load and simplify the dataset 
Our SMS text messages dataset has 5 columns if you read it in pandas: v1 (containing the class labels ham/spam for each text message), v2 (containing the text messages themselves), and three Unnamed columns which have no use. We’ll rename the v1 and v2 columns to class_label and message respectively while getting rid of the rest of the columns.

2. Explore the dataset: Bar Chart:
It’s a good idea to carry out some Exploratory Data Analysis (EDA) in a classification problem to visualize, get some information out of, or find any issues with your data before you start working with it. We’ll look at how many spam/ham messages we have and create a bar chart for it.

3. Explore the dataset: Word Clouds
For my project, I generated word clouds of the most frequently occurring words in my spam messages.

4.Handle imbalanced datasets:
To handle imbalanced data, you have a variety of options. I got a pretty good f-measure in my project even with unsampled data, but if you want to resample, see this.
5. Split the dataset
 6. Apply Tf-IDF Vectorizer for feature extraction
 7.Train our Naive Bayes Model
Vedha: 8.Check out the accuracy, and f-measure:
It’s time to pass in our Tf-IDF matrix corresponding to x_test, along with the true output labels (y_test), to find out how well our model did!

First, let’s see the model accuracy:

print("classifier accuracy {:.2f}%".format(classifier.score(features_test_transformed, y_test) * 100))
Accuracy of our Naive Bayes classifer: 96.35%
8. Finally, Spam classifier is now ready
9. Load and simplify la 9th varaikum stepsda
