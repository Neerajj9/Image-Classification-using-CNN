# Convolutional-Neural-Networks
Keras based CNN models for classification related problems .

The Dataset for both Image Classification problems from Kaggle :

Hydra : https://www.kaggle.com/c/invasive-species-monitoring

Plant Seedling Classification : https://www.kaggle.com/c/plant-seedlings-classification

The approach for both problems was to first Augment the data and then feed a pretrained network to extract features . These extracted features were
then trained on a Neural Network to gain final results . I also tried using ensembling (SVM and Deep Logistic on the extracted features)  but a neural network 
performed better .


Hydra :

The problem statement was to classify invasive species of Hydra and non-invasive species . I have used transfer learning (a pretrained VGG model)
and Data Augmentation to get results .




Plant Seedling Classification :

The problem statement was to classify different plant seedlings into specific types . A Resnet model is used here to get results instead of A VGG .
