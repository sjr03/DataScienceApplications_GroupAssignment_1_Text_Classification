# DataScienceApplications_GroupAssignment_1_TextClassification
### Project Introduction
This project is part of data science applications course at University of Ottawa under Professor Dr. Arya Rahgozar
### Project Status
Completed
### Introduction
The purpose of this project is to train a machine learning model to predict the Author/Genre based on the text from the books. 
### Methods Used
Machine Learning, Data Visualisation, Data Cleaning.
### Technologies Used
Python, Google Collab, Pandas, NLTK, SciKit Learn.
### Description
To start with we are taking 5 different samples from project Gutenberg digital books which are of five different authors, and of same genre. Our model predicts the author/genre based on the text from the books. The data cleaning methods that we use are Stop words, Garbage words removal and Stemming. As a part of feature engineering we are doing BoW, TF - IDF. The machine learning algorithms that we compared are SVM, KNN, Decision Tree, XGBoost. We are getting 96% of accuracy which on massaging is reduced to 74%.
### Getting Started
1. Download the .ipynb file
2. diff_genre_da - The variable used to assign data of different genres and different authors
3. same_genre_da - The variable used to assign data of same genres and different authors
4. This can be fed to the model by passing it through the function - get_book_sample
5. To pass the book link use the below format in the variable "book_list" = [('https://gutenberg.org/files/69983/69983-0.txt', 'Thomas Wright')]. First parameter is the link and second parameter is the Author name. If we want to use genre change the seond parameter to genre.
6. Run all the code at once

### Group Number 
15
### Group Members
Dinesh Udayakumar, Padmasri Padmasri, Ragul Santhamani Jayaraman, Tharun Nagaveera Marthandan
