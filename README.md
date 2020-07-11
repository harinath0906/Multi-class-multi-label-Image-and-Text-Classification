# Objective

In this project, I will solve a multi-label classification task. Each sample in this dataset includes:
* an image
* one or more (upto 18) labels,
* a short caption that summarizes the image.
I will implement an image classifier combined with text classifier that predicts the labels of image and caption.

# Dataset
The dataset can be accessible from [here](https://drive.google.com/drive/folders/1lIjeKO2F938ztS5vpdOdtk_sQFQ2c_I4?usp=sharing). The dataset contains:
* train.csv - contains imageid, labels and caption
* test.csv - contains imageid and caption
* Images.zip - contains images of all imageids

# Models
The trained models can are saved and are accessible from [here](https://drive.google.com/drive/folders/1-PUS8HpKpCmRoJyngSWNpTFoL6mzY6xQ?usp=sharing)

# Modules
The below modules / techniques have been used in this project.
* CNN Network
* ResNet50
* PyTorch
* Bi-LSTM
* Binary Cross Entrophy with weighted loss
* Early Stopping
* Feature extraction from CNN and Bi-LSTM
* Text preprocessing

# Results
The report [here](https://github.com/harinath0906/Multi-class-multi-label-Image-and-Text-Classification/blob/master/Project_report.pdf) contains the extensive details of all modules used with their background, all experiment results and the details of the neural network.
