## Using Natural Language Processing Techniques to Improve Manual Test Case Descriptions

This repository contains the source code of the experiments that we performed for our automated framework to improve the descriptions of new manual test cases. This work was published at the 44th International Conference on Software Engineering (ICSE) - Industry track (2022). In you can find the paper [here](https://markosviggiato.github.io/resources/Markos_ICSE_SEIP_2022.pdf).

Currently, the framework automatically analyzes test cases written in natural language and provides three improvement recommendations:

* Recommendations to **improve the terminology** of a new test case description based on existing test case descriptions through language modeling

* Recommendations of **potentially missing test steps** for a new test case through frequent itemset and association rule mining

* Recommendations of **similar test cases** that already exist in the test suite through a similarity detection technique that we proposed in a [prior work](https://markosviggiato.github.io/resources/Markos_arxiv_submitted_2021.pdf)


---


## Structure of directories
 
 The following directories contains the source code of all the approaches that were part of our experiments. 


 - [language-models](/language-models/): contains the notebooks with the source code of our experiments with statistical and neural language models.
 
 - [association-rules](/association-rules/): contains the notebooks with the source code of our experiments with frequent itemset and association rule mining.
 
 
 The notebooks with the source code of our experiments with different test case similarity techniques can be found in the [repository of our previous work](https://github.com/asgaardlab/21-markos-test_case_similarity_technique-code)


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


 - [Matplotlib 3.0.3](https://matplotlib.org/)

    `
    pip install matplotlib
    `


 - [Plotly 4.14.3](https://plotly.com/)

    `
    pip install plotly
    `


 - [Scikit-learn 0.21.1](https://scikit-learn.org/stable/)

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
