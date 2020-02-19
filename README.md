# Musk_Non-Musk_molecule_classifier

The compounds are classified as either ‘Musk’ or ‘Non-Musk’ compounds based on their  their chemical features and isomeric conformation. The classification model used is CNN with binary_cross_entropy as the loss function and Adam as the optimizer.

***Use of binary_cross_entropy:***
binary_cross_entropy is used because the number of classes to identify are 2.

***Use of Adam:***
Adam is used because it is computationally efficient, has little memory requirements, Hyper-parameters have intuitive interpretation and typically require little tuning.
Adam realizes the benefits of both AdaGrad and RMSProp and achieves good results fast.

***Preprocessing:***
First dealing with the missing values if any.(there are none in the dataset)
As there are a large No. of features(166) which will be used to predict the molecule type. We can remove the features with high correlation as correlated features in general don't improve models.

Removal of correlated features make learning algorithm faster as less features usually mean high improvement in terms of speed.


