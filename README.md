# Data Science Portfolio
This repository represent my portfolio which contains the data science and machine learning projects I worked on through academia and self-learning.

## Projects:

### [Scene Classification using Transfer Learning](https://github.com/saeidesm/scene-classification-transfer-learning)
* Used **CNNs** and **Transfer Learning** to classify different scenes
* Three different models (MobileNetV2, Xception, and Inc-ResNetV2) adopted as the base model
* Fine-tuned the models to our small dataset of scene pictures
* Results demonstrated 94% accuracy in scene classification
<br>_Keywords(Classification, CNN, Transfer Learning, Fine-Tunning)_

### [Traffic Congestion Prediction](https://github.com/saeidesm/traffic-prediction-using-lstm)
* **Dataset:** City od Madrid traffic administrators deployed over 3000 traffic sensors to gather various traffic parameters including average traffic speed, density and occupancy. Aggregated data is published as an IoT service using a [RESTful API](https://informo.madrid.es/informo/tmadrid/pm.xml) and data is updated every 5 minutes. 
* Investigated the correlation between different data points in order to feed the network
* Used **stacked LSTM** to fit three days of Madrid traffic data
* Used the sliding window analogy to predict next four steps of speed, density and occupancy 
* Analyzed the predicted data to make decision upon the congestion occurence
* Results demonstrated 99% accuracy in parameters prediction
<br>_Keywords(Time Series Data, LSTM, Traffic Prediction)_

### [Movie Recommender System](https://github.com/saeidesm/movie-recommender-system)
* **Dataset:** The TMDB 5000 movie dataset
* Explored and analyzed the dataset
* Clean the datasets and merge all avible datasets together.
* Preprocess each columns to get the important key words and put all together in the "tags" column
* Used the **Bag of Words** technique for the vectorization
* Computed the cosine angle between all vectors(movies)
* Recommended top 6 movies base on the cosine angle(similarity)
* Used Streamlit to visualize the movie recommender as a web application

### [Fraudulent Firms Classification](https://github.com/saeidesm/fraud_audit/blob/main/fraud-audit.ipynb)
* Explored and analyzed the dataset 
* Cleansed the dataset and imputed the data where needed
* Optimized hyperparameters through a cross-validated grid search 
* Used different ML models (**Logistics Regression, KNN SVM, MLP, Decision Tree, Random Forest, Gradient Boosting**) to classify firms with fraud risk
* Results demonstrated 100% accuracy in fraudulent firms classification
<br>_Keywords(Classification, Logistics Regression, KNN SVM, MLP, Decision Tree, Random Forest, Gradient Boosting, Cross Validation, Grid Search)_

### [Bankruptcy Prediction from Qualitative Parameters](https://github.com/saeidesm/qualitative_banking/blob/main/qualitative_bankruptcy.ipynb)
* Explored and anlysed the dataset 
* Cleansed the dataset and imputed the data where needed
* Optimized hyperparameters through a cross-validated grid search 
* Used different ML models (**Logistics Regression, KNN SVM, MLP, Decision Tree, Random Forest, Gradient Boosting**) to predict bankruptcy
* Results demonstrated 100% accuracy in bankruptcy prediction
<br>_Keywords(Classification, Logistics Regression, KNN SVM, MLP, Decision Tree, Random Forest, Gradient Boosting, Cross Validation, Grid Search)_

### [Lending Club Paying Back Prediction](https://github.com/saeidesm/lending-club-default-prediction/blob/main/LendingClub_Keras_Project.ipynb)
* Processing the data before trining the model, takes several steps, including: 
   - Removing loan features with significant missing data, or that aren't known to investors
   - Exploring, transforming, and visualizing the data
   - Finding the most correlated features through correlation process 
   - Creating dummy variables for categorical features 
* Used **sequential model** to predict if a client will pay back their loan or not. 
* Results demonstrated that the model achieved a high precision of 0.88 on the test set. The F1 score is 0.93.
<br>_Keywords(Classification, Sequential model, Keras)_

