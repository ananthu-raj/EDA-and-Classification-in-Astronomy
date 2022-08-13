# EDA-and-Classification-in-Astronomy

Blog related to this project explaining Supervised Vs Unsupervised learning. 
https://medium.com/@ananthuraj/supervised-machine-learning-intuition-f481f181f625

Astronomical datasets are typically very large, and manually classifying the data in them is effectively impossible.
This study documents the importance of Data Analysis and its interpretation in physics through familiarizing with analysis tools available in python. The way we see data has changed over the centuries and yet the fundamentals of analysis remain more or less the same.




To perform Exploratory Data Analysis on Sloan Digital Sky Survey (SDSS) Data Release 17 (DR17). This catalogue contains photometric data for all objects viewed through a telescope and spectroscopic data for a small part of these. Train ML classification models on the labelled Photometric data which is spectroscopically classified with labels. The EDA helps to choose the right models for the dataset. All the information gained from conducting EDA helps to choose a data model. 

We will apply the trained models which have the highest accuracy when trained on the training set , on new unclassified data which is accessible from the SDSS server. 

![image](https://user-images.githubusercontent.com/60540680/184470500-1d5ac375-a617-44da-9d88-70d6b77fccad.png)

Various machine learning algorithms will be used to predict three classes - Stars , Galaxies , Quasars. We will primarily consider KNN , SVM , random forest algorithms for classification and other models will be used if the EDA gives such inferences. Scaling of data will be done to get better results. The results will help astronomers and astrophysicists carry out further studies.

![Screenshot 2022-08-13 at 11 29 39 AM](https://user-images.githubusercontent.com/60540680/184470892-156a1ef7-632c-4f00-9492-a5de20e80dd0.png)

The results of the SDSS are electronically available to the scientific community and the general public, both as images and as precise catalogues of all objects discovered. By the end of the survey, the total quantity of information produced is about 15 terabytes. 
The data consists of 5,00,000 observations of space taken by the SDSS. Every observation is described by 17 feature columns and 1 class column which identifies it to be either a star, galaxy or quasar.

The dataset offers plenty of information about space to explore. Also, the class column is the perfect target for classification practices. 
     

![image](https://user-images.githubusercontent.com/60540680/184470954-993d563f-5117-4959-8584-107ae53f635e.png)

The classification models under consideration are :
> k-Nearest Neighbours.
 
> Decision Trees.

> Naive Bayes.
 
> Random Forest.
 
> Gradient Boosting.
 
> SVM

![Screenshot 2022-08-13 at 11 30 24 AM](https://user-images.githubusercontent.com/60540680/184470923-62ee814a-d700-4e19-bd17-22918c7294a1.png)
