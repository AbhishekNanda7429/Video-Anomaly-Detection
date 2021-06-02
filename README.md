# Video-Anomaly-Detection
Detecting anomaly using AlexNet,VGG16,MxNet

UCSD DATASET: http://www.svcl.ucsd.edu/projects/anomaly/dataset.html

The first model AlexNet is trained on UCSD dataset which is downloaded from the above link.
Step1: import all the required libraries.
Step2: set the train folder dataset and test folder dataset.
Step3: proceed acoording to the ipynb shells.
Step4: set the parameters for the model.
Step5: compile the model and save it using callback functions.
Step6: train the model and use the matplot library to plot the accuracy and loss.

NOTE: the same procedure goes for VGG16 too.

The third model is MxNet, it is different from others because it is an autoencoder.
Step1: first import the libraries including mxnet. if you dont have mxnet then use "!pip install mxnet" .
Step2: here the dataset we are using is imported from the kaggle. https://www.kaggle.com/bladerunnerrachel/ucsd-anomaly-dataset
Step3: after importing follow the procedure in shells.
Step4: train the model and save the model.
Step5: use matplot library to plot the anomaly in frames. it will show frame-wise where the anomaly is present using a red dot on it.

All the steps mentioned above are in brief so kindly use your brain if you have any doubts!!
