# Data Science Portfolio
This repository represent my portfolio which contains the data science and machine learning projects I worked on through academia and self-learning.

## Projects:

### [Traffic Congestion Prediction](https://github.com/saeidesm/traffic-prediction-using-lstm)
* **Dataset:** City od Madrid traffic administrators deployed over 3000 traffic sensors to gather various traffic parameters including average traffic speed, density and occupancy. Aggregated data is published as an IoT service using a [RESTful API](https://informo.madrid.es/informo/tmadrid/pm.xml) and data is updated every 5 minutes. 
* Investigated the correlation between different data points in order to feed the network
* Used **stacked LSTM** to fit three days of Madrid traffic data
* Used the sliding window analogy to predict next four steps of speed, density and occupancy 
* Analyzed the predicted data to make decision upon the congestion occurence
* Results demonstrated 99% accuracy in parameters prediction
<br>_Keywords(Time Series Data, LSTM, Traffic Prediction)_
 
### [Scene Classification using Transfer Learning](https://github.com/saeidesm/scene-classification-transfer-learning)
* Used **CNNs** and **Transfer Learning** to classify different scenes
* Three different models (MobileNetV2, Xception, and Inc-ResNetV2) adopted as the base model
* Fine-tuned the models to our small dataset of scene pictures
* Results demonstrated 94% accuracy in scene classification
<br>_Keywords(Classification, CNN, Transfer Learning, Fine-Tunning)_
