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

The following dependencies are required to run the notebooks on your local machine:

 - Python 3.7
 
  
 - [Numpy 1.19](https://numpy.org/)

    `
    pip install numpy
    `


 - [Pandas 1.1.5](https://pandas.pydata.org/)
 
    `
    pip install pandas
    `

  
 - [matplotlib 3.0.3](https://matplotlib.org/)

    `
    pip install matplotlib
    `
    
 
 - [scikit-learn 0.21.1](https://scikit-learn.org/stable/)

    `
    pip install scikit-learn
    `
    

 - [NLTK 3.4.1](https://www.nltk.org/)

    `
    pip install nltk
    `
    
 - [Spacy 3.0.1](https://spacy.io/usage)

    `
    pip install -U pip setuptools wheel
    `
    `
    pip install -U spacy
    `
    `
    python -m spacy download en_core_web_sm
    `
    
 - [Transformers 4.3.2](https://huggingface.co/transformers/)

    `
    pip install transformers
    `   
    
 - [Torch 1.7.1+cpu](https://pytorch.org/)

    `
    pip install torch
    `    
    
 - [TensorFlow 2.4.1](https://www.tensorflow.org/)

    `
    pip install tensorflow
    `  
    
 - [TensorFlow_Hub 0.11.0](https://www.tensorflow.org/hub)

    `
    pip install tensorflow-hub
    `  
    