# BayesianClassifier
This is our Bayesian Classifier. It was made as an assignment for the Artificial Intelligence course. 

## Running the classifier on the blogs
Compile all files, and run src/testing/EmailTester.java.

## Running the classifier on the e-mails
Compile all files, and run src/testing/BlogTester.java.

## FAQ

### Where can I find the classifier?
You can find our Multinomial Naive Bayes Classifier under src/classifier/MultinomialNaiveBayesClassifier.java.

### How are the files read?
Read the commentary in src/fileparser/FileUtils.java.

### How can I change what files are used for training, and testing?
Just put the files in the correct directory. For example, if you want to add some female blogs as test set, move it to db/blogs/F/test. The new file will be used the next time you run the tester. For the e-mails, it wasn't given which ones to use as training, and which one as test sets, so by default, the first 10% are used as training set, and the others as test set, instead of using folders.

### Can I also use custom sets to classify?
Of course! If for example you have some jokes, which can be classified as either good or bad, just put each classification in a different folder. Then, create a Java class in the src/testing package, for example called JokeTester.java. You can base your implementation on the existing classes in that package. 