# Wells-Fargo-Challenge-2022
**Combining the use of a Tensorflow Universal Sentence Encoder and a Neural Network for Transaction Category Classification**

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Conclusion](#Conclusion)


## General info
This project is the code used to solve the Wells Fargo Campus Analytics Challenge 2022. The challenge objective is as follows: "Build a model to predict transaction categories using the 10 (ten) distinct categories that a transaction may fall into."

There are two excel (.xlsx) files included in the repository which were provided by Wells Fargo for model training and testing.

## Technologies
Project is created with following technologies and packages:
* Python 3.8.5
* pandas 1.4.2
* NumPy 1.19.2
* scikit-learn 0.23.2
* tensorflow-hub 0.12.0
* stop-words
* Jupyter Notebook

## Setup
The first step to recreating results is to install all required technologies and packages in the [Technologies](#technologies) section. Verify that all three files in this repository are in the same local folder and then all of the cells in the notebook (.ipynb) file can be run in order to see results.

## Conclusion
By utilizing a Universal Sentence Encoder as well as a Multi-Layer Perceptron model, we can predict transaction category with a 79% accuracy. A flowchart of the analytical process can be seen below.


![Ben_Gonzalez_Wells_Fargo_CAC_2022](https://user-images.githubusercontent.com/87507821/180665376-35cb90b5-ce23-4cde-8bc3-30f129f76f17.png)
