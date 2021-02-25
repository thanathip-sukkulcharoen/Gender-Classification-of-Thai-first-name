# Gender Classification of Thai first name in English

This is my senior project about machine learning which its aim is to classify gender from Thai first name in English on social media.

The accuracy of this model is 92.3% which evaluated by using 10-fold cross validation method.

**Introduction Video**

[![Demo Video](http://img.youtube.com/vi/clCirGEKvSM/0.jpg)](http://www.youtube.com/watch?v=clCirGEKvSM "Senior Project Demo Day")]

## Tables of Content
* [Demo](#demo)
* [Features](#features)
* [Prerequisite Library](#prerequisite-library)
* [Methodology and Result](#methodology-and-result)
* [Installation](#installation)
* [Note](#note)
## Demo
Live code here --> [Google Colab](https://colab.research.google.com/drive/1GmORDKHSyS2TyMjnzbgxXU90_L2-YF70?usp=sharing)
## Features
Predict Thai first name in English which collected on social media with accuracy of 92.3%
## Methodology and Result 
Please see "Summary Report.pdf" for explaination but it is written in Thai language.
## Prerequisite Library
* [pandas](https://pandas.pydata.org/) 
* [numpy](https://numpy.org/)
* [sklearn](https://scikit-learn.org/stable/)
* [nltk](https://www.nltk.org/)
* [statistics](https://docs.python.org/3/library/statistics.html)
* [pprint](https://docs.python.org/3/library/pprint.html)

## Installation
1. Just git clone this repository or download it.
2. I recommend using [Jupyter Notebook](https://jupyter.org/) or [Google colab](https://colab.research.google.com/) to open code.
3. Make sure that "name_dataset.xlsx" is in the same folder as "SeniorProject.ipynb"
## Note
* All evaluations are measured by using 10-fold cross validation except **every tuning model part** which measured by using 3-fold cross validation because the program was running too long.
* There are **duplicate** names in dataset because I didn't collect names by myself. I developed a tool to help me collect these names but the tool is not perfect,it rarely collects the same name.
* Originally,I didn't intend to push this code to github, so the code is look messy in some part because I just wanted quick results but I tried to organize the code as much as possible.
