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
The trained models are saved and are accessible from [here](https://drive.google.com/drive/folders/1-PUS8HpKpCmRoJyngSWNpTFoL6mzY6xQ?usp=sharing)

# Modules
The below modules / techniques have been used in this project.
* CNN Network
* ResNet50
* Fine tuning pretrained ImageNet model
* PyTorch
* Bi-LSTM
* Binary Cross Entropy with weighted loss
* Early Stopping
* Feature extraction from CNN and Bi-LSTM
* Text preprocessing

# Results
The report [here](https://github.com/harinath0906/Multi-class-multi-label-Image-and-Text-Classification/blob/master/Project_report.pdf) contains the extensive details of all modules used with their background, all experiment results and the details of the neural network.

# References
* https://pytorch.org/docs/stable/torchvision/models.html
* https://github.com/gskdhiman/Pytorch-Transfer-learning-Multi-Label-image-Classification/blob/master/pytorch-resnet50-starter.ipynb
* https://heartbeat.fritz.ai/basics-of-image-classification-with-pytorch-2f8973c51864
* https://www.learnopencv.com/pytorch-for-beginners-image-classification-using-pre-trained-models/
* https://pytorch.org/docs/stable/torchvision/transforms.html
* https://discuss.pytorch.org/t/multiclass-classification-skewed-data-problem-and-labeling/68437
* https://pytorch.org/tutorials/beginner/finetuning_torchvision_models_tutorial.html
* https://medium.com/udacity-pytorch-challengers/ideas-on-how-to-fine-tune-a-pre-trained-model-in-pytorch-184c47185a20
* https://discuss.pytorch.org/t/weights-in-bcewithlogitsloss/27452
* https://discuss.pytorch.org/t/multiclass-classification-skewed-data-problem-and-labeling/68437
