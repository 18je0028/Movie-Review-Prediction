

                          We want to solve the problem of binary classification of IMDB movie reviews.In total we have around 50k reviews.In that we have 25k reviews marked as good, another 25k bad.

                      Here, it’s not easy to get started with machine learning right away because we don’t have the matrix ; we need to prepare it. We will use a simple approach: bag of words model. Features of the review will be represented by indicators of the presence of each word from the whole corpus in this review.We will use CountVectorizer to prepare the document matrix.When the dataset is prepared we will use traintestsplit with testsize=0.3, i.e We will train our data on 70% and test it for 30%.We will use logistic regression to see the accuracy on our test set. We will also use logistic regression using pipeline and RandomForestClassifier using pipeline and observe accuracy on test set.
                      
