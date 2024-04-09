# Literature Summarizer and Clustering with NLP and Deep Learning
- CM3070 Final Project
- Using Covid-19 Open Research Dataset (CORD-19) from Kaggle
- Final Report Code

This repository contains the final assignment and project for Goldsmiths, University of London module CM3070.

## Introduction
This project is titled, “Literature Summarizer and Clustering using NLP and Deep Learning”, with the aim of creating a software application that can process textual data in literature to provide a summary and group related literature together. This application requires the use of NLP to process the textual data in literature and ML techniques to help group the literature together. This project would focus on the use of ML techniques to cluster the data and follows template 1 of the CM3015 “Machine Learning and Neural Networks” module, “conducting deep learning on a public dataset”. The dataset used for this project is obtained from Kaggle, “COVID-19 Open Research Dataset Challenge (CORD-19)”, which is an open dataset that has over 1,000,000 scholarly articles about COVID-19, and related coronaviruses. This huge dataset of literature provides a good opportunity to develop the application.

## Goals
There are 4 goals for this project:
1. Aid researchers in sieving through all the textual data in a piece of literature.
2. Provide a summary of the literature presented.
3. Group related literature together, helping researchers narrow their scope.
4. Create a data visualization tool to view the related literature.

## Approach
- Preprocess the Data
- Read data from dataset
- Extract key features from each document
- Load data into dataframes
- Clean data
- Natural Language Processing (Step 1)
- Text Preprocessing: (Stop Words Removal); (Text Parsing); (Tokenization)
- Text Representation: (Text Vectorization)
- Machine Learning Processing (Step 2)
- Classification: (Dimensionality Reduction->PCA); (Clustering Algorithm); (Dimensionality Reduction->t-SNE)
- Topic Modeling
- Data Visualization (Step 3)
- Plot Setup
- Show Plot

## Final Evaluation and Conclusion
In this project, I aim to create a deep learning model and a software application that can help summarize and cluster literature together. The primary models used for this project are Natural Language Processing (NLP) and Machine Learning (ML) algorithms and techniques to process textual data to be clustered into groups. The dataset used for this project was a huge dataset of academic papers obtained from Kaggle, titled: “Covid-19 Open Research Dataset (CORD-19)”.

The application is able to read and store the data into data frames from the dataset. Data processing such as cleaning and the use of NLP techniques to transform the data into discrete data structures to be usable for machine learning and deep learning models. ML techniques are utilized to help cluster the literature files and were successfully plotted on an interactive graph. Users can directly interact with the graph to view the different literature and have its metadata shown for the user’s convenience.

To evaluate the success of this project, I will reiterate the goals of this project:
1. Aid researchers in sieving through all the textual data in a piece of literature.
2. Provide a summary of the literature presented.
3. Group related literature together, helping researchers narrow their scope.
4. Create a data visualization tool to view the related literature.

There are many areas that this application have performed well and successfully met the goals of this project:
1. Processed large amounts of textual data (goal 1)
2. Used 2 different deep learning models to conduct clustering, and properly evaluated their performance to determine the best model for this project (goal 3)
3. Produced a useful plot and visualization with its every data point in its associated clusters (goal 4)
4. This project conducted on Jupyter Notebook allows it to be used without reprocessing the data, making it 'portable'

However, there are also many limitations and failures that this application did not manage to achieve:
1. The nature of academic papers and its contents limited the effectiveness of the clustering algorithms
2. The performance of either clustering algorithms were subpar and did not produce good clusters
3. Did not manage to summarize the literature presented, this project only utilized the abstract as the summary
4. Did not manage to utilize all of the data in the dataset due to language and resource constraints
