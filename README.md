# ccomplex


Study for predicting commit conflict complexity using Machine-Learning

## files

* *results-all.arff:* Weka results for all the datasets, with all the ML algorithms. 
* *results-ann.arff:* Weka results for different configurations of the Artificial Neural Network
* *experiment-10fold-10rep.exp:* Weka experiment configuration for all datasets and all ML algorithms. It shows the different configurations for Naïve Bayes, Artificial Neural Network and J48
* *protocol.txt:* Details of the labeling protocol 

## folders

* *jenkins:* Contains the datasets for Jenkins
* *voldemort:* Contains the datasets for Voldemort

## Datasets

The datasets have been named like this:

_project_ - _type_ - _set_

* _project_ : can be either "jenk" or "vold". Self-explanatory
* _type_ : refers to the type of conflict considered, it can be "commit" (for merge conflict), "test" (for test failures) or "build" (for build failures)
* _set_ : it determines if the dataset contains all features ("all") or only the ones chosen by feature selection ("filtered")

