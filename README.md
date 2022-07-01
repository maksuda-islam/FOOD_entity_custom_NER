# Custom Name Entity Recognition model using SpaCy
--------------------------------------------------------------------------------

SpaCy is a library for advanced Natural Language Processing in Python and Cython. The project has a Name Entity Recognition(NER) model for the custom "FOOD" and the other pre-existed entities of SpaCy.

## Documentation
-----------------------------------------

## Dataset Preparation
To prepare the json file a online annotating tool [NER Text Annotator](https://tecoholic.github.io/ner-annotator/) is used.<br> 
Giving a text file as a input the annotation tool gives back a json file(spacy NER dataset format) after annotating it manually using preferable labels.

Later On, I used a json parser to parse that file and formatting it into my desired data format(in order to work easily with that) and wrapped it into a function, which I called in my ipynb file to access.

## Setting up the Project
----------------------------------------------------------------------
After cloning the project run this command: pip3 install -r requirement.txt
