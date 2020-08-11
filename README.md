# Final-Project

Data Preprocessing:
1) Python
Please note that the datasets used for this project have already been created and included in the zip file. If wanting to go through the processing step, first use the file entitled Data Preprocessing.ipynb. To run the code, you will need to first enter two paths. The first calls upon the Kaggle dataset entitled sentiment_analysis_for_financial_news.csv (section entitled “Read in data…”).  The second is an output path, which is in the last block of code. 
This code is responsible for removing punctuation, numbers, trialing and leading white space, and for performing stemming.
2) R
The code in this section can be found in the .R file named r script for creating document term matricies.R. For this code to run successfully, you will need to enter in a total of three paths. The first will be for the cleaned data generated form the Preprocessing.ipynb file (python post processed data.csv). The next two paths will be output paths of your choosing.
This code is responsible for creating document term-frequency matrices (With and without stop words). 
Model Building and Evaluation:

# Model Building and Evaluation 
1)	Python
Note that you can start at this step if you desire since the dataset has already been processed. You will need the Model Building.ipynb file for this section. This file requires three paths to entered. The first for the Kaggle dataset (sentiment_analysis_for_financial_news.csv), the second for the document term-frequency matrix with stop words (document_frequency_matrix.csv), and lastly for the document term-frequency matrix without stop words (document_frequency_matrix_no_stop.csv). This file performs all the model building and evaluation. 

Data source - https://www.kaggle.com/ankurzing/sentiment-analysis-for-financial-news

