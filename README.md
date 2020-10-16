# Detroit-BlightViolation-Ticket
Predict whether a given ticket will be paid on time using City Detroit public data.

This project showcases the application of ML algorithms, ensemble test, and techniques of resampling imblanced dataset.
You can find more details about the study in my blog post [here](https://kate-d.medium.com/predict-whether-a-given-ticket-will-be-paid-2967ca93ec1c).

## Dataset

The dataset is supplied in the [kaggle competition](https://www.kaggle.com/c/detroit-blight-ticket-compliance), based on the [data challenge](http://midas.umich.edu/mdst/) from the Michigan Data Science Team (MDST) partnered with the City of Detroit.

## Installation

There should be no necessary libraries to run the code beyond Anaconda distribution of Python. The code should run without issues in Python3.

## File descriptions

There are 3 notebooks available here to showcase work related. The workflow is organized and documented in three Jupyter notebooks as follows: 

- `1_dataProcessing.ipynb`: Data is loaded, cleaned and preprocessed; Exploratory data analysis
- `2_modelling.ipynb`: Apply machine learning algorithms and corss-validation
- `3_resampling.ipynb`: Experiment of different imblanced data techniques
- `data`: Folder saving original dataset and the preprocessed data
- `plots`: Folder saving the corresponding output plots in the analysis 
