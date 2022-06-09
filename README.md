# Predicting Bike Sharing Patters
This repo includes a code that predicts amount of bikes that will be rented from a bike sharing establishment for a given time interval. This project is part of the Udacity Deep Learning Nanodegree. 

The notebook is very detailed and includes all of the steps. So, here we will give an high-level overview of what the project entails. Given a tabular data of the number of bikes rented over days, we format it using ```pandas```. Then, we implement a neural network from $\textit{scratch}$, implementing forward and back propagation with SGD as the optimizer by just using numpy functionality. This part can be found in ```my_answers.py```. Then, in the notebook, we implement the training loop and run it. We see that the training and validation error decrease quite well. We then test the model that is trained for 3000 epochs and get very accurate predictions. 

## Future work: 
Use XGBoost for this task since it works really well on tabular data. 