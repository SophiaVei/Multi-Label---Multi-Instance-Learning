# Multi-Label & Multi-Instance Learning
This work aims to consolidate the objects of learning from data
multi-labeling and learning from bags of cases. We are working
with the DeliciousMIL dataset, which contains a set of documents, where the
each document is considered as a bag of sentences. We are vectorizing them with sklearn's feature_extraction.text module.  

Part A  
In the first part we will work on the subject of learning from data
multiple tags. We apply two learning techniques from multi-label data
in the above data, where the representation of each document concerns the words that
includes (bag of words). We present and comment on the results of the experiments
based on the given train and test splits. Tip: in this type of sparse representations,
linear models and/or linear SVMs usually perform well.  

Part B  
In the second part we will work on the problem of multi instance learning. We focus on the most common of the 20 classes so we can deal with one
binary classification problem. We consider that each document is a bag of sentences. We group the sentences of the training set and represent each
document based on the groups to which its sentences belong. We try one more
model that represents each document based on all its sentences. Wr present and
comment on the results of these two approaches.
