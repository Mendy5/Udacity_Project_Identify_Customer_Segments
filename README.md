# Udacity Introduction to Machine Learning with TensorFlow Project III: Identify Customer Segments

This repository contains all related files of the Udacity Machine Learning with TensorFlow Project II: Identify Customer Segments

## Installation
All the dependencies libraries are in the spec-file.txt. Please run the command below to clone the conda environment of the project:
```
conda create --name udacity_dev_workspace --file spec-file.txt
```

## Data Source
[Udacity_AZDIAS_Subset]() contains the demographics data of the general population of Germany
[AZDIAS_Feature_Summary]() contains a summary of feature attributes for demographics data
[Udacity_CUSTOMERS_Subset]() contains demographics data of the customers of the mail order company
[Data_Dictionary]() contains detailed information file about the features in the provided datasets

## Project Motivation
This project is to identify the target customers of the mail order company by applying the unsupervised models and comparing the difference between the segements of general population and the segements of the customers of this company.

## Results
Found target customer segments by applying the PCA and clustering. One target customer segments formed by customers who have these characteristics:

- average earners
- very low financial interest
- new houseowners
- very low movement patterns
- High to very high share of 1-2 family houses in the microcell

More details are in the [Identify_Customer_Segments.ipynb]() notebook.

# Licensing, Authors, Acknowledgements
Must give credit to Bertelsmann Arvato Analytics for the data.
