PART 1:

AIM: Implement an object detection model for highlighting human faces to automate the process of providing information of cast and crew while streaming using Semantic Segmentation model.

Jupyter NB: Movie_Scene_Face_Detection_Part1
Dataset:Train_images.npy

Actions perform:

1.Basic EDA
2.Check for distribution of data
3.Create features (images) and labels (mask) using input dataset .
4.Split into train-test sets
5.Design a face mask detection model using Unet semantic segmentation model.
5.Design your own Dice Coefficient and Loss function.Train, tune and test the model.
6.Evaluate the model using testing data

PART 2:
AIM : Help create dataset for image classification by returning coordinates of the face detected in the profile images using haarcascade.
Jupyter NB: CreateFaceCoordinatesDataset


PART 3:
AIM: Differentiate between the images of celebrities using concept of Siamese network/Feature extractor.Identify the faces of celebrities obtained from Pinterest. 
Build a CNN model to classify the celebrities.

Jupyter NB: FaceRecognitionSimilaity
Dataset:Aligned Face Dataset from Pinterest.zip

Actions perform:

1.Basic EDA
2.Load the dataset and create the metadata.Check some samples of metadata.
3.Create features (images) and labels (mask) using input dataset .
4.Load the pre-trained  VGG16 model and weights.
5.Generate Embedding vectors for each face in the dataset
5.Build distance metrics for identifying the distance between two given images
6.Use PCA for dimensionality reduction.
7. Build an SVM classifier to map each image to its right person.
8. Predict using the SVM model


PART 4:
AIM: Detect vehicles and impute bounding boxes in a video file.

Jupyter NB: DetectVehiclesMovingTraffic
Dataset:Aligned Any video file of moving vehicles


