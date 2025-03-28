# MOOD CLASSIFICATION OF SONGS USING SPOTYFY DATASET.										 
## INTRODUCTION			 
In this project we utilized a spotyfy dataset to classify songs into different mood categories based on  their audio features. We implemented a **Decesion Tree
Classifier** for mood classification and used K-maens clustering to group songs into 11 mood categories. 

## DATASET AND FEATURES
The dataset was obtained from spotyfy, containig various audio features for each song. The key features used for mood classification included: Energy,valence,
instrumentalness,Tempo,Danceability,speechness,loudness...
WE conducted audio feature analysis such as correlation Analysis, to find relationship between different audio features. EDa to understand the distribution of features using histogram,boxplot...

## MOOD CLUSTERING USING K-MEANS.
We used k-means clustering to categorize songs into 11 distinct mood groups. Means grouped songs based on similarities in their audio features, forming distinct mood categories such as Happy,sad, Energtic, Relaxed, Angry, Romatic....

## DATA PREPROCESSING
Before applying classification we performed essential preprecessing steps:                           
1. ENCODING CATEGORICAL DATA.
Categorical variables such as mood our target class was encoded using Label Encoding to convert them into numerical format
2. STANDARDIZATION.
We used mimmaxscaler to normalize numerical features contributed equally to the model.      
3. DIMENSIONALITY REDUCTION(PCA).
Principal compenent analysis was applied to reduce dimensionality while preserving variance, improving model efficiency.

## MOOD CLASSIFICATION USING DECISION TREE.
To classify songs into the identified mood categories, we trained a Decesion Tree classifier. The model was trained using a labeled dataset where mood labels
were assigned based on the K-means clusters.

## MODEL TRAINING AND EVALUATION
   -   Training Data: 80% of the dataset was used for trainig and 20% was reserved for testing

   -   Performance metrics: Accuracy,precision,Recall and F1 score were used to evaluate the model

   -    Results: The Decision Tree classifier performed well, with an accuraccy of approximetly 98%, indicating strong classification ability. 












                        



