I used twitter data from a kaggle competion as my training and test data set to train different Machine learning classical algorithm models to detect sentiments
(positive, negative and neutral) for each of the tweets.
The models were NB Bernoulli ,Linear SVC model, Logistic Regression Model and Random Forest Model and compared the results among them inorder to find the model with 
the best confusion matrix.

Here I mainly focused on Exploratory Data Analyis (EDA) and data visualization to get more insights in our dataset.
Generated meta features - 1. Difference In Number Of words of Selected_text and Text
                          2. Jaccard Similarity Scores between text and Selected_text

Preprocessed and cleaned the data - 
● Removed stopped words  
● Lemmatization,
● Remove text in square brackets.
● Remove links.
● Remove punctuation.
● Remove words containing numbers.
● Replacing same letters in sequence- more than twice into just double letter

Used different methods to visualize our data before and after prepossing. 
Visualizations used such as word clouds , kernel distribution graph, bar diagram , funnel charts, tree of unique words/common words, sentiment wise differences etc


