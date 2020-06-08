# stack_overflow_2019
Analysis of the Stack Overflow 2019 Annual Developer Survey data.

## Table of contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name='installation'></a>

The code in the Jupyter Notebook for the analysis has been written in **Python 3**, and is using the packages **Numpy, Pandas, Matplotlib, zipfile and Sci-kit Learn**, all of which are included in the Anaconda distribution of Python.

## Project Motivation <a name='motivation'></a>

This project was done as part of the Udacity Data Scientist Nanodegree. The aim is to use the data made available by Stack Overflow in its Annual Developer Surveys for the years 2017, 2018 and 2019 in order to investigate and answer the following questions:

* **Are more and more developers becoming data scientists?**
* **What programming languages are favored by data scientists?**
* **What features recorded in the 2019 survey stand out the most for data scientists?**

For the first 2 questions, descriptive statistics combining the datasets for the 3 years were used, and for the last question, a classification model was build using the random forest ensemble method. All the code, as well as comments and analysis, are available in the Jupyter Notebook uploaded on this page.

## File Descriptions <a name='files'></a>

This repository contains a Jupyter Notebook, in which all the code to answer the questions above can be found. Markdown cells throughout the code aim to guide the reader through the analysis and the choices that were made.

Copies of the zip files containing the original data that was used in the analysis are also on this repository. These files can also be downloaded directly from Stack Overflow [here](https://insights.stackoverflow.com/survey).

## Results <a name='results'></a>

Results and analysis are concisely explained in the Jupyter Notebook. A less technical overview of the results is presented in the Medium post [here](https://medium.com/@jackbot71/what-language-should-you-learn-as-a-data-scientist-173475523291).

## Licensing, Authors, and Acknowledgements <a name='licensing'></a>

A great thank you to Stack Overflow for capturing this very interesting data, and making it publicly available. The data is licensed under the [Open Database License (ODbL) v1.0](https://opendatacommons.org/licenses/odbl/1.0/).

The rest of the code found in the Notebook is free for anyone to use.
