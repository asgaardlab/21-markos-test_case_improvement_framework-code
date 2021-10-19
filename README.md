## Using Natural Language Processing Techniques to Improve Manual Test Case Descriptions

This repository contains the source code of the experiments that we performed for our automated framework to improve the descriptions of new manual test cases. Currently, the framework automatically analyzes test cases written in natural language and provides three improvement recommendations:

* Recommendations to **improve the terminology** of a new test case description based on existing test case descriptions through language modeling

* Recommendations of **potentially missing test steps** for a new test case through frequent itemset and association rule mining

* Recommendations of **similar test cases** that already exist in the test suite through a similarity detection technique that we proposed in a [prior work](http://asgaard.ece.ualberta.ca/papers/preprint/markos_preprint_test_similarity.pdf)


---


## Structure of directories
 
 The following directories contains the source code of all the approaches that were part of our experiments. 


 - [language-models](/language-models/): contains the notebooks with the source code of our experiments with statistical and neural language models.
 
 - [association-rules](/association-rules/): contains the notebooks with the source code of our experiments with frequent itemset and association rule mining.
 
 
 The notebooks with the source code of our experiments with different test case similarity techniques can be found in the [repository of our previous work](https://github.com/asgaardlab/test-case-similarity-technique)


---


## Dependencies

The following dependencies are required to run the notebooks on your local machine.