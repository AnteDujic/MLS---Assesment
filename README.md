# MACHINE LEARNING AND STATISTICS | 2022/2023
### AUTHOR: ANTE DUJIC
<hr style="border:2px solid gray"> </hr>

This repository contains notebooks for the practicals and final assessment done for Machine Learning and Statistics module on ATU, Ireland. The layout of this repository is:

```
MLS-Assessment
│   .gitignore
│   README.md                   
│
└───Practicals
│   │   01-statistics.ipynb
│   │   02-models.ipynb
│   │   03-parameters.ipynb
│   │   04-learning.ipynb
│   │   
│   └───Img                     
│       │   single_input.svg
│       │   single_neuron.svg
│   
└───Final Assessment
│   │   05-anomaly_detection.ipynb
│   │   
│   └───Img                     
│       │   window.drawio.svg
```


### HOW TO RUN THIS PROJECT?
<hr style="border:2px solid gray"> </hr>

1. Clone the repository from the [GitHub](https://github.com/AnteDujic/MLS-Assessment)
2. Download [Anaconda](https://docs.anaconda.com/anaconda/install/windows/)
3. Download [cmder](https://cmder.app/)
4. Run Jupyter Lab or Jupyter Notebook
5. Open the wanted notebook in Jupyter

Alternatively, click on the icons below to see the notebooks in your browser.

PRACTICALS: <br>
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/AnteDujic/MLS-Assessment/tree/main/Practicals/)

FINAL ASSESMENT: <br>
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/AnteDujic/MLS-Assessment/tree/main/Final%20Assesment/)
    
    
### :file_folder: PRACTICALS
<hr style="border:2px solid gray"> </hr>

This folder contains notebooks based on the Module lectures, which are centered around different topics related to Machine Learning. It also contains the img file, with diagrams used in those notebooks. The main part of each notebook are the exercises, done as weekly assignments for the Module. The rest of the notebooks is heavily based on the lectures, with certain parts being left out or further developed, with a purpose of building a narrative around the mentioned exercises. Below are listed all the notebooks and a brief explanation of each exercise.

#### 01 - STATISTICS
***

There are three exercises in this notebook. First two are centered around A Lady Tea Test, and the third one around Student T-test.
- Exercise 1 - Calculate the minimum number of cups of tea required to ensure the probability of randomly selecting the correct cups is less than or equal to 1%
    - Bonus: How many would be required if you were to let the taster get one cup wrong while maintaining the 1% threshold?
- Exercise 2 - Use scipy's version of Fisher's exact test to simulate the Lady Tasting Tea problem.
- Exercise 3 - Take the code from the Examples section of the scipy stats documentation for independent samples t-tests and explain how it works.

#### 02 - MODELS

There are two exercises in this notebook.

- Exercise 1 - Plot the absolute value function. Research and explain why the absolute value function is not typically used in fitting straight lines to data.
- Exercise 2 - Fit a straight line to the given data points, using numpy.polyfit, scipy.optimize.minimize and scipy.optimize.curve_fit. Explain if a straight line is a good model for the given data points.

#### 03 - PARAMETERS
***

There is one exercise in this notebook.

- Exercise 1 - Use numpy's polyfit to fit polynomials to the given data sets.

#### 04 - LEARNING
***

There are no exercises in this notebook.

### :file_folder: FINAL ASSESSMENT
<hr style="border:2px solid gray"> </hr>

This folder contains one notebook - Anomaly detection, done as a final assessment for this Module. The task was to recreate the anomaly detection code from [Keras website](https://keras.io/examples/timeseries/timeseries_anomaly_detection/), explain and further develop the concepts contained in this official documentation. Below is the breakdown of the mentioned Notebook.

#### 05 - ANOMALY_DETECTION
***
###### • INTRODUCTION
Briefly explaining the following concepts:
 - Keras
 - Time series
 - Anomaly detection
 - Autoencoder
 
######  • DATA
Giving an overview of the datasets used to train and test the model for anomaly detection.

###### • PREPROCESSING
Preparing the datasets for the machine learning and explaining the techniques used.

###### • BUILD A MODEL
Creation and compilation of the model. Brief explanation of the main concepts used for model building.

###### • TRAIN THE MODEL
Training the previously built model.

###### • ANOMALY DETECTION
Finally, using the model to detect anomalies.

###### • CONCLUSION


### REFERENCES
<hr style="border:2px solid gray"> </hr>
- LISTED IN CORRESPONDING NOTEBOOKS