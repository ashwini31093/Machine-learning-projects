AIM:
To localize cars and identify the model to which it belongs.
Dataset used to train the model : Standford cars dataset.
https://www.kaggle.com/jutrera/stanford-car-dataset-by-classes-folder




Actions performed: 
1.Basic EDA : Map the training and testing images to its classes and annotations
2.Analyse the dimensions of the data. Visualise the data
3. Design,Train tune and test AIML image classifier model.
4. This design of this task is a two-step approach:
    a. Localize the possible presence of car :  transfer learning using EfficientNet
    b. Classification the car using the localized car image : Basic CNN, transfer learning, hyperparameter tuning.
5. Compare the results from the above steps. 
6. 6.Pickle the best performing model


