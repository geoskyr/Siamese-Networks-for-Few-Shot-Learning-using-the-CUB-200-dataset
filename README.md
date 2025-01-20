This is an Image Classification task on the CUB-200 dataset using Siamese Networks. Siamese Networks are used in Few Shot Learning scenarios where  we dont have sufficient training and testing data to traditionally train and test a ML model like a Convolutional Neural Network. Siamese Networks create positive (images belong in the same class) and negative pairs (images do not belong in the same class) of images using the training dataset and the CNN is trained with a loss function that is calculated based on the euclidean distance of the feature vectors of the 2 images of the pair. The evaluation and testing of the model is done through episodes created from the testing dataset . The classes of the training and testing datasets do not overlap as we want to increase the generalization ability of the model and evaluate the accuracy on data it has not seen during training.


1.Download the dataset from here: https://drive.google.com/file/d/18Ri71ZPUu5FY12AqejrI9_DWy4ywahRv/view?usp=drive_link .
2.Upload the `.rar` file to your Google Drive in the `/MyDrive/` folder.

The .ipynb uses mounting so when you upload the dataset in your Google Drive you can start executing the code.
